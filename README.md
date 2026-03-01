# Arduino Uno R3 Custom 2-Layer PCB Design

This repository contains a complete Altium Designer project for a custom-engineered **Arduino Uno R3** compatible board. This design optimizes the classic Uno architecture into a compact 2-layer PCB while maintaining full pin compatibility with the standard R3 shield ecosystem.


## 🛠 Project Overview
- **Microcontroller:** ATmega328P (DIP-28 package)
- **USB-to-Serial:** Integrated SMD interface
- **PCB Layers:** 2 Layers (Signal + Power/Ground)
- **Board Dimensions:** Standard Arduino Uno Form Factor
- **Software Compatibility:** Fully compatible with the Arduino IDE

## 📂 Repository Structure
* **/Project Files:** Contains the Altium `.PrjPcb`, `.SchDoc`, and `.PcbDoc`.
* **/Outputs:** Manufacturing-ready Gerber files, NC Drill files, and BOM (Bill of Materials).
* **/Images:** 2D/3D renders of the board for quick preview.

## 📐 Design Specifications
- **Layer 1 (Top):** Signal routing and primary component placement.
- **Layer 2 (Bottom):** Dedicated Ground Plane for noise reduction and thermal stability.
- **Trace Widths:** Optimized for power delivery (VCC/GND) and high-speed data integrity.
- **Via Size:** Standard 0.3mm drill / 0.6mm diameter for cost-effective manufacturing.


## 🚀 Manufacturing Notes
To manufacture this board, use the provided files in the `/Outputs` folder. 
- **Material:** FR-4
- **Thickness:** 1.6mm
- **Surface Finish:** HASL (with lead) or ENIG
- **Solder Mask:** Blue (to match standard Arduino aesthetic)
- **Silkscreen:** White

## 📝 How to Use
1. Clone this repository: `git clone [Your-Repo-Link]`
2. Open `28pins_Antariksh_unoR3_V1I1.PrjPcb` in **Altium Designer**.
3. To view without Altium, refer to the PDF schematics in the `/Outputs` folder.

---
Designed with ❤️ by [Pulkit]
