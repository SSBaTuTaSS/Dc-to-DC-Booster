# DC-DC Step-Up Converter

This project is a compact **DC-DC Boost Converter** design capable of stepping up an input voltage from **2.7V – 12V** to an output range of **4.5V – 14.7V**.  
The circuit is based on the TPS61288RQQR boost controller IC, designed in KiCad for PCB manufacturing.  

---

## 📐 Circuit Overview
- Input Voltage: 2.7V – 12V  
- Output Voltage: 4.5V – 14.7V (adjustable)  
- Controller IC: TPS61288RQQR (TI)  
- Output Current: 3A – 4A continuous, up to 6A peak
- Topology: Boost Converter  
- PCB Stackup: 2 Layers (FR4)  
- Key Components: Inductor, fast diode, MOSFET, bypass capacitors, and adjustable potentiometer  
- Application: Prototyping, powering devices requiring higher voltage from low-voltage sources (battery, USB, etc.)

 ---

Specifications of Circuit

| Parameter        | Value                                  |
|------------------|----------------------------------------|
| Input Voltage    | 2.7V – 12V                             |
| Output Voltage   | 4.5V – 14.7V (Adj)                     |
| Controller IC    | TPS61288RQQR                           |
| Topology         | Boost Converter                        |
| Output Current   | 3A – 4A continuous, up to 6A peak |
| Efficiency       | ~85% (typical)                         |
| PCB Stackup      | 2-layer FR4                            |
| Frequency        | High frequency                         |

---

## 📐 KiCad Schematic
Below is the KiCad schematic for the DC-DC Booster circuit:

![DC-DC Booster Schematic](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/images/schematic2.png)

---

## 🖼️ PCB Layout
2D PCB layout generated in KiCad (**2-layer, FR4 substrate**):  

![PCB Layout](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/images/PCB2D%20V2.png)

---

## 🎨 3D PCB View
3D model rendered with KiCad Viewer:  

![3D PCB](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/images/PCB%203D.png)  
![3D PCB](https://github.com/SSBaTuTaSS/Dc-to-Dc-Booster/blob/main/images/3D%20V2.png)


---

## 📁 Files
- `DCtoDCboost.kicad_pro` → KiCad project file  
- `DCtoDCboost.kicad_pcb` → KiCad PCB layout (2-layer FR4 stackup)  
- `DCtoDCboost.sch` → KiCad schematic file  

---

## ⚡ Features
- Compact design  
- Adjustable output voltage    
- High-frequency switching allows the use of small inductors and capacitors  
- Suitable for prototyping and embedded systems  
  

⚠️ **Warning**: Ensure the output does not exceed the rating of your connected device.  


## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
