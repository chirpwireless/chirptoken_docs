# Data Collection and Geolocation Mechanics

### **How Kage Collects Data from Wi-Fi, Cell Towers, and BLE Networks**

Kage continuously scans the wireless environment around a user’s device to identify nearby **Wi-Fi access points**, **cell towers**, and **Bluetooth Low Energy (BLE)** signals. Each detected signal contains unique identifiers such as SSID, BSSID, or cell tower IDs, along with metadata like signal strength (RSSI), frequency band, and transmission characteristics.

These detections are gathered **passively and anonymously** — Kage does not capture or transmit personal data or network content. Instead, it collects only the technical information necessary to characterize each signal’s presence and relative strength.

By combining these observations across thousands of devices and regions, Kage builds a massive dataset that represents the **radio fingerprint of the physical world**. This forms the foundation of Chirp’s **Geopositioning Database**, enabling positioning and mapping capabilities independent of satellite signals.

***

### **How GPS Provides Initial Reference Points for Triangulation**

While Kage’s ultimate goal is to achieve **GPS-free geopositioning**, GPS data still plays a vital role during the early mapping phase. When available, GPS readings serve as **anchor points** for newly detected signals.

Each time Kage records a signal, it associates it with the GPS coordinates and timestamp of the detection. Over time, as multiple Data Hunters detect the same signals from different locations, Chirp’s algorithms can infer the signal’s fixed position — even when GPS is not available in future detections.

This process allows the network to **bootstrap location intelligence**: GPS data provides the initial reference, and repeated signal detections by many users refine and eventually replace it with signal-based positioning.

***

### **Importance of Geospatial Accuracy and Timestamping**

Every data point collected by Kage includes precise **geolocation, timestamp, and device orientation** information.\
These attributes are critical for three reasons:

1. **Spatial Context** – Location data ensures that signals are correctly mapped in relation to one another.
2. **Temporal Relevance** – Timestamping enables Chirp to identify signal drift or infrastructure changes over time.
3. **Redundancy Detection** – Comparing multiple readings of the same signal from different contributors allows Chirp to validate accuracy and identify anomalies.

This meticulous tagging ensures that Chirp’s network grows not just in scale, but in **fidelity and trustworthiness**.

***

### **Triangulation vs. Trilateration**

#### **Triangulation**

Triangulation determines a device’s position by measuring the **angle** between known reference points — typically using differences in signal direction or pattern. In Chirp’s context, triangulation helps estimate where a device is relative to nearby signals with known positions, especially when signal strengths vary across directions.

#### **Trilateration**

Trilateration, on the other hand, calculates position based on **distance** rather than angle. By measuring the relative signal strength (RSSI) or time-of-flight (ToF) from multiple sources, the system determines where the signal zones overlap.\
If a device detects three or more signals with known locations, Chirp’s positioning engine can compute its exact position as the **intersection point** of these signal ranges — similar to how GPS calculates position using satellites.

***

### **How Chirp Uses Overlapping Signal Zones for GPS-Independent Positioning**

Chirp’s positioning engine combines triangulation and trilateration models to generate precise coordinates without satellite input.\
It builds **signal zones** — virtual bubbles representing the probable range of each transmitter (Wi-Fi router, BLE beacon, or cell tower). When multiple zones overlap, Chirp computes the device’s position inside that intersection region.

As more Kage users scan an area, the system continuously refines these signal zones through:

* **Redundant observations** from different devices and angles
* **Signal decay modeling** (RSSI attenuation over distance)
* **Temporal consistency** (how signals behave over time)

This process allows Chirp to produce accurate **indoor and low-power geopositioning**, even in environments where GPS fails — such as warehouses, underground structures, or dense urban areas.
