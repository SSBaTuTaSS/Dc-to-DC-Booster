# DC-DC Step-Up Converter

This project is a compact **DC-DC Boost Converter** design capable of stepping up an input voltage from **2.7V – 12V** to an output range of **4.5V – 14.7V**.  
The circuit was simulated in **LTspice** and designed in **KiCad** for PCB manufacturing.

---

## 📐 Circuit Overview
- Input Voltage: **2.7V – 12V**  
- Output Voltage: **4.5V – 14.7V** (adjustable)  
- Topology: **Boost Converter**  
- Key Components: Inductor, fast diode, MOSFET, bypass capacitors, and adjustable potentiometer  
- Application: Prototyping, powering devices requiring higher voltage from low-voltage sources (battery, USB, etc.)

## 📐 KiCad Şematik

Below is the KiCad schematic for the DC-DC Booster circuit:

![DC-DC Booster Şematik](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/pcb/schematic.png)

---

## 🖼️ PCB Layout
2D PCB layout generated in KiCad:  

![PCB Layout](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/pcb/PCB%202D.png)

---

## 🎨 3D PCB View
3D model rendered with KiCad Viewer:  

![3D PCB](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/pcb/PCB%203D.png)
![3D PCB](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/pcb/image.png)

This provides an early preview of component placement, soldering feasibility, and mechanical compatibility.  

---

## 📁 Files
- `DCtoDCboost.kicad_pro` → KiCad project file  
---

## ⚡ Features
- Compact design  
- Adjustable output voltage  
- High-frequency switching allows the use of small inductors and capacitors  
- Suitable for prototyping and embedded systems

---
