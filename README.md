# ESP32-Expansion-Board
ESP32 Expansion Board designed by Arpan Mukherjee for simplified prototyping with ESP32-Devkit V1. Features organized pin headers, regulated +12V to +5V power via 7805T, jumpers for flexible interfacing, and clear silkscreen labels. Includes schematics, PCB layouts, and documentation.


# ESP32 Expansion Board

Designed by **Arpan Mukherjee**  
Date: 03/02/2026  

This repository contains the design files, schematics, and PCB layouts for an **ESP32 Expansion Board**. The board is built to simplify prototyping and interfacing with the ESP32-Devkit, providing organized pin headers, regulated power supply, and easy access to GPIOs.

---

## 📌 Features
- Compatible with **ESP32-Devkit V1**.
- Organized pin headers for:
  - Power: 3V3, 5V, VIN, GND
  - Digital I/O: D1 – D39
  - UART: RX0/TX0, RX2/TX2
  - Special pins: EN, VP, VN
- On-board **7805T voltage regulator** for +12V input → +5V output.
- Decoupling capacitors (C1, C2) for stable power.
- Jumper headers (JP1 – JP4) for flexible interfacing.
- Clear silkscreen labels for easy identification.
- Compact and symmetrical PCB layout for neat prototyping.

---

## Schematic
<img width="1536" height="1046" alt="ESP_SCHEMATIC" src="https://github.com/user-attachments/assets/f15ef96a-1274-40a7-99a0-8a59f4048b66" />

## Top Layer
<img width="2023" height="1830" alt="TOP_IMAGE" src="https://github.com/user-attachments/assets/fe1992ea-f932-420e-b117-ef3ceef61725" />
## Bottom Layer
<img width="5775" height="5224" alt="BOTTOM_IMAGE" src="https://github.com/user-attachments/assets/4c5b838b-7382-4f95-8fee-6a935109b42d" />

## Top Layer (Prior to Fabrication)
<img width="3000" height="2000" alt="ESP_SCH_TOP" src="https://github.com/user-attachments/assets/5a16f917-a4af-49e6-a9af-8aed7013d231" />

## Bottom Layer (Prior to Fabrication)
<img width="3000" height="2000" alt="ESP_SCH_BOTTOM" src="https://github.com/user-attachments/assets/ddc4305d-fa79-4735-bfa1-f2a259304d72" />


## 📂 Repository Contents
- **TOP.pdf** → Top layer PCB layout  
- **Bottom.pdf** → Bottom layer PCB layout  
- **Schematics** → ESP32 Expansion Board circuit diagram  
- **PCB Images** → Rendered PCB layouts for visualization  

---

## ⚡ Hardware Overview

### Power Section
- Input: +12V DC  
- Regulator: 7805T → +5V output  
- Outputs: +5V, 3V3, GND available on headers  

### Pin Mapping
| Left Header | Right Header | Center Header |
|-------------|--------------|---------------|
| 3V3, GND, D15, D2, D4, D5, D18, D19, D21, RX0, TX0, D22, D23 | +5V, GND, D13, D12, D14, D27, D26, D25, D33, D32, D35, D34, VN/D39, VP/D36, EN | IO15, IO2, IO4, IO16, IO17, IO5, IO18, IO19, IO21, IO3, IO1, IO22, IO23 |

---

## 🔧 How to Use
1. Connect **ESP32-Devkit V1** to the expansion board.  
2. Provide **+12V input** to the power terminal.  
3. Use headers to interface sensors, modules, or external circuits.  
4. Configure jumpers (JP1–JP4) as needed for custom connections.  

---

## 📸 Visuals
PCB layouts and schematics are included in this repository (`TOP.pdf`, `Bottom.pdf`, and schematic diagrams).  

---

## 📺 Additional Resources
- YouTube Channel: [The ElectroPath](https://www.youtube.com/@The_ElectroPath)  

---

## 📜 License
This project is released under the **MIT License**. You are free to use, modify, and distribute with attribution.

---

## 🙌 Acknowledgments
- Designed and developed by **Arpan Mukherjee (ECE)**  
- Institution: **BCREC**  
