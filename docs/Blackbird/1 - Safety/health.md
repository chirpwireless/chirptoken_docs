---
id: 'health'
title: 'Health considerations'
sidebar_position: 1
---

# Health considerations {#health-considerations}

The topic of the potential health effects of electromagnetic fields (EMF) from LoRaWAN and other radio frequency (RF) technologies is a contentious one. This article aims to provide an overview of the current state of knowledge and research on this subject.

LoRaWAN, a low-power wide-area network protocol, operates at subGHz frequencies or 2.4GHz. There is no specific research available on the health effects of LoRaWAN, but it is not considered different from other RF technologies in this regard. Therefore, we can refer to generic studies on RF frequencies, including WiFi, which also operates at 2.4GHz.

The majority of these studies suggest that there is no direct evidence of EMF having an adverse effect on the human body. However, the World Health Organization (WHO) has classified EMF under the "Possibly carcinogenic to humans" category, leading to extensive regulation on acceptable EMF levels. These regulations are primarily based on the Precautionary Principle and vary significantly from country to country. Even within the European Union (EU), some countries enforce stricter levels than others.

Several key documents provide further insight into this issue:

1. "Establishing a dialogue on risks from electromagnetic fields" [(WHO, 2002)](WHO_-_2002_-_Establishing_a_dialogue_on_risks_from_electromagnetic_fields.pdf): This document focuses on communicating with the public about the potential risks of EMF.

2. "Health effects of WiFi radiation: a review based on systematic quality evaluation" [(Dongus et al, 2021)](Dongus_et_al_-_2021_-_Health_effects_of_WiFi_radiation_a_review_based_on_systematic_quality_evaluation.pdf): This paper reviews studies on the health effects of WiFi radiation and concludes that there is no evidence to suggest detrimental health effects from WiFi exposure below regulatory limits.

3. "Guidelines for limiting exposure to EMF" [(ICNIRP, 2020)](ICNIRP_-_2020_-_Guidelines_for_limiting_exposure_to_EMF.pdf): The International Commission on Non-Ionizing Radiation Protection (ICNIRP) is a non-governmental organization that advises the EU Commission and the WHO. Their guidelines aim to protect people and the environment from the adverse effects of non-ionizing radiation.

4. "Potential health effects of exposure to electromagnetic fields" [(SCENIHR, 2015)](SCENIHR_-_2015_-_Potential_health_effects_of_exposure_to_electromagnetic_fields.pdf): The Scientific Committee on Emerging and Newly Identified Health Risks (SCENIHR) provides this report for the EU Commission.

The maximum transmission power for both subGHz and 2.4GHz LoRaWAN concentrators is 27dBm or 500mW. With an 8dB omni antenna, this equates to 35dBm or 3.2W on the horizontal plane. The radiated power at 1m is 0.76W/m2, at 2m it's less than 0.1W/m2, and at 10m it's 0.75mW/m2. The ICNIRP sets the reference level for exposure at 4.3W/m2, which is approximately the exposure limit for the general public in most EU countries. The USA sets this higher (6W/m2), while China sets it lower (0.4W/m2). Some countries have more restrictive levels near schools or hospitals, where they can be as low as 0.1W/m2. As long as the antenna is outdoors and more than a few meters away from any human body, it will comply with these regulations.

Indoor gateways with lower gain antennas radiate a maximum of 0.8W, which is also within the maximum level at 1m distance in all countries.

The SAR (Specific Absorption Rate) needs to be specifically measured. As we are FCC and CE certified for our gateway products we are under the maximum limits for sure. As you can see from the CE report - page 25/26, the equipment is under the limits for all RF parts - WiFI, LoRa and Cellular (RAK7289CV2) - [CE report](https://downloads.rakwireless.com/LoRa/RAK7289V2/Certification/RAK7289C_RAK7289V2_CE_Certification.pdf).

For further understanding, the following tools can be used to convert power units:

1. [Power Conversion - RapidTables.com](https://www.rapidtables.com/convert/power/index.html)
2. [Power Conversion - Powerwatch.org.uk](https://www.powerwatch.org.uk/science/unitconversion.asp)