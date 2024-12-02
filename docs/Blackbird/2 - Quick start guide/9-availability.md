---
sidebar_position: 9
id: "9-availability"
title: "Recommendations for Improving Gateway Availability"
---

# Recommendations for Improving Gateway Availability

To ensure maximum gateway availability, it is necessary to follow a series of recommendations covering various aspects of its operation. These recommendations include requirements for connectivity, software updates, physical location of the device, and operating conditions.

## 1. Registration and Verification of the Gateway
The gateway must be registered and verified to ensure Rewards. Read more [here](https://docs.chirptoken.io/Chirp%20Network/Blackbird/Quick%20start%20guide/5-registration)

## 2. Ensuring Quality Internet Connection
- **Wired Connection**: It is preferable to use a wired connection as it provides the most stable connection. Use a Category 5 Enhanced (Cat5e) cable for connecting the POE cable. For additional protection, cover the connections with electrical insulation tape.
    * It is recommended to use a POE switch that will be connected through an uninterruptible power supply (UPS).
- **Wi-Fi Connection**: If a wired connection is not possible, use Wi-Fi. Ensure its stability and the absence of interference.
- **SIM Card**: In the absence of a wired or Wi-Fi connection, use a SIM card. Check that the SIM card is activated and the balance is topped up.
    * The SIM card can be used as a backup communication channel in case of problems with the primary internet connection.
    * SIM cards in gateways are supplied already inside the gateway from Chirp. The balance on each SIM card should be topped up at least to a small amount to ensure continuous communication.
    * To activate the SIM card, contact [support](mailto:help@chirpwireless.io).
- **Communication Channel Setup**: All communication channels, including LAN and WLAN, can be configured simultaneously to ensure redundancy, so the gateway can switch to another channel if one connection is lost.
    * The priority of communication channels can be individually configured, ensuring optimal switching between them depending on availability and stability.

## 3. Ensuring Uninterrupted Power Supply
- **Recommendation**: It is desirable for the gateway to be connected to a UPS to prevent shutdowns in case of power outages.

## 4. Physical Location of the Gateway
- For more detailed information about the physical location and installation of the gateway, you can read here.
- Ensure there are no metal barriers nearby that could block the GPS signal.
- Check that the gateway is installed in a location with a good GPS signal.
- Ensure that there are no other gateways within a 300-meter radius. If multiple gateways are connected within a 300-meter radius, only the first registered gateway will receive rewards.
- Make sure there are no military objects or other sites using GPS signal jammers nearby.

## 5. Additional Measures
- Check the correct installation of antennas. Improperly installed antennas can lead to signal degradation. For more detailed information about antenna installation, you can read [here](https://docs.chirptoken.io/Chirp%20Network/Blackbird/Quick%20start%20guide/2-installation-scenarios/), including an [article](https://docs.chirptoken.io/Chirp%20Network/Blackbird/Quick%20start%20guide/3-placementrewards/) on the importance of antenna placement for signal coverage and crypto rewards.
    * Attention! Do not turn on the gateway without antennas, as this will result in the failure of the LoRaWAN module. This will be considered a non-warranty case! The gateway must be connected to the network only with the antennas connected.
    * Never turn on the gateway without antennas; this can lead to transmitter damage.
    * In rural areas, it is recommended to use routers with cellular support and signal amplifiers.

## 6. Checking Compatibility with Operators
- Ensure that the SIM card is supported by telecom operators in your country. In some countries, there may be restrictions that need to be considered.

## 7. Accounting for External Factors
- Monitor weather conditions and other external factors that may affect the stability of the internet connection.
