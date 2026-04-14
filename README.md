# Boardoza XL6007 Symmetrical ±5V Power Supply Module

The **Boardoza XL6007** is a high-efficiency **DC-DC step-up switching regulator module** designed to generate a **symmetrical ±5V output** from a **single supply** input source. Built around the **XL6007E1** high-frequency switching regulator, this board provides both +5V and -5V outputs, making it ideal for analog and dual-supply applications.

Thanks to its fixed **400kHz switching frequency** and integrated boost converter topology, the module ensures stable, efficient voltage conversion with minimal external components. The symmetrical output capability allows balanced current draw from both rails, supporting up to **500mA total output current**. This makes it especially suitable for operational amplifier circuits, sensor interfaces, audio preamplifiers, and other low-power analog designs requiring dual-polarity supply.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)

| Front Side | Back Side |
|:---:|:---:|
| ![B-XL6007-BRK Front](./assets/XL6007%20Front.png) | ![B-XL6007-BRK Back](./assets/XL6007%20Back.png) |

---

## Key Features

- **Symmetrical ±5V Output:** Generates both **+5V and -5V** from a single input supply.  
- **Boost Converter Topology:** Based on the **XL6007E1** high-efficiency DC-DC step-up regulator.  
- **High Output Capability:** Supports up to **500mA total output current** (shared between outputs).  
- **High Switching Frequency:** Fixed **400kHz** operation for stable and efficient performance.  
- **Good Efficiency:** Up to **~90% efficiency** depending on load and conditions.  


---

## Technical Specifications

**Model:** XL6007  
**Manufacturer:** Boardoza  
**Manufacturer IC:** XLSEMI  
**Topology:** Boost Switching Regulator (Configured for Dual Output)  
**Input Voltage:** 3V DC to +12V DC  
**Output Voltage:** +5V and -5V  
**Maximum Output Current:** Up to 500mA (Total Symmetrical)  
**Switching Frequency:** 400kHz (Fixed)  
**Efficiency:** Up to 90% (IC dependent, application specific)  
**Operating Temperature:** -40°C to +125°C  
**Board Dimensions:** 40mm x 60mm  

---

## Board Pinout

### ( J1 ) Input Connector

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | VIN | Supply Voltage Input |
| 2 | GND | Ground |

### ( J2 ) Output Connector

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | +5V | Positive 5V Output |
| 2 | GND | Ground |
| 3 | -5V | Negative 5V Output |

---

## Performance Graph

### Output Current vs Input Voltage

<img src="./assets/XL6007 Output Current vs Input Voltage.png" alt="Output Current vs Input Voltage Graph" width="600"/>

---

## Board Dimensions

<img src="./assets/XL6007 Dimensions.png" alt="B-XL6007-BRK Dimension" width="450"/>

---

## Step Files

[Boardoza XL6007E1.step](./assets/XL6007%20Step.step)

---

## Datasheet

[XL6007 Datasheet.pdf](./assets/XL6007%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**
### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
