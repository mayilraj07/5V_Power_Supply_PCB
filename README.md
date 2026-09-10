# 5V Linear Power Supply Unit (PSU) PCB Design
A compact, robust, and professional-grade **5V Regulated DC Power Supply** designed using **KiCAD**. This project steps down and regulates an unregulated DC input into a stable 5V output suitable for powering microcontrollers (Arduino, ESP32, Raspberry Pi Pico), sensors, and low-power embedded devices.
---
## 📌 Features & Highlights
* **Stable 5V Output:** Constant voltage regulation using industry-standard voltage regulators.
* **Input Protection:** Filter capacitors to reduce voltage ripples and high-frequency noise.
* **Power Indicator:** On-board LED indicator for immediate visual status of the power supply.
* **Compact Footprint:** Optimized 2-layer PCB layout designed with professional component placement rules.
* **Noise Suppression:** Dedicated input/output decoupling capacitors placed adjacent to the regulator pins.
---
## 🛠️ Circuit Topology & Power Flow
The board follows a clean, single-direction power flow topology for minimal signal interference:
`DC Input / Connector` ➡️ `Input Filter Capacitors` ➡️ `5V Voltage Regulator` ➡️ `Output Filter Capacitors` ➡️ `Power LED Indicator` ➡️ `5V Terminal Output`
---
## 📐 Technical Specifications

| Specification | Value / Description |
| :--- | :--- |
| **Input Voltage** | 7V - 12V DC |
| **Output Voltage** | 5.0V DC (Regulated) |
| **EDA Tool Used** | KiCAD |
| **PCB Layers** | 2-Layer Board |
| **Power Track Width** | 0.8 mm – 1.0 mm (High Current Capacity) |
| **Signal Track Width** | 0.3 mm |
| **Copper Pour** | Top & Bottom Ground Plane (GND Zone) |

---
## 🖼️ Screenshots & Previews

### 3D Board View
### Top View
<img width="1920" height="1082" alt="5V_Power_Supply_Top_View" src="https://github.com/user-attachments/assets/98f800c4-3378-4d4c-bf95-18a3848df140" />

### Bottom View
<img width="1920" height="1082" alt="5V_Power_Supply_3D_bottom_View" src="https://github.com/user-attachments/assets/99022edf-5661-4770-8a59-d4c83dd65c6f" />

### Isometric View
<img width="1920" height="1082" alt="5V_Power_Supply_3D_Isometric_View" src="https://github.com/user-attachments/assets/09d24de0-9495-4e2c-a9e2-39b9eb5d5b78" />

### PCB Layout Design
<img width="990" height="238" alt="5V_Power_Supply_PCB_Layout" src="https://github.com/user-attachments/assets/d207b7c4-3bb4-4d24-92aa-20c5ef531d32" />

### Schematic Diagram
<img width="825" height="359" alt="5V_Power_Supply_Schematic" src="https://github.com/user-attachments/assets/3b74fbf6-3c52-4064-bbec-b865eaa93d4e" />

## 📂 Project Structure
```text
├── Hardware/           # KiCAD Schematic and PCB Layout files
├── Production/         # Production-ready Gerber files (.zip) and (BOM)
├── Docs/               # Images & 3D Render
└── README.md           # Project Overview
``` 
---

## 👤 Author & Acknowledgment
* **Designed by:** mayilraj07(https://github.com/mayilraj07)
* **Tool:** KiCAD EDA
