# CMOS Operational Amplifier Design and Layout Extraction  

This repository contains the design, simulation, and analysis of a **two-stage CMOS Operational Amplifier (Op-Amp)** implemented in **LTSpice** and validated using **Spectre simulations**. The work was carried out as part of the *Analog & Digital VLSI Design* course under the supervision of **Dr. Anu Gupta, BITS Pilani**.  

---

## 📌 Project Overview  
The project focuses on the **design, optimization, and layout extraction** of a CMOS Op-Amp. Key steps included:  
- Circuit design and transistor sizing (W/L ratios) to achieve stability and efficiency.  
- Simulation of performance parameters (gain, phase margin, CMRR, PSRR, slew rate, settling time, power, and output swing).  
- Physical layout design ensuring **design-rule compliance**, minimized parasitics, and area optimization.  

---

## ⚡ Key Results  
- **3dB Bandwidth:** ~100 kHz  
- **Phase Margin:** 60°  
- **DC Gain:** 15.7  
- **CMRR:** 69.7 dB  
- **PSRR:** 61.2 dB  
- **Slew Rate:** 90 V/µs  
- **Settling Time:** 50 ns  
- **Power Consumption:** 0.42 mW  
- **Output Swing:** ≥ 1V  

---

## 🛠 Tools & Technologies  
- **LTSpice** – Circuit simulation and analysis  
- **Cadence Spectre** – Performance validation  
- **Synopsys / Layout tools** – Layout design and extraction  

---

## 📂 Repository Structure  
- `Circuit_Diagrams/` → LTSpice schematic and netlist files  
- `Plots/` → Simulation plots (AC gain, phase, CMRR, PSRR, etc.)  
- `Layout/` → Extracted layout files and DRC reports  
- `Report.pdf` → Full project report (design + results)  

---

## 📖 References  
- *Design of Analog CMOS Integrated Circuits* by Behzad Razavi  
- LTSpice and Cadence documentation  
- IEEE Xplore resources on CMOS Op-Amp design  

---

## 👨‍💻 Authors  
- Kumar Krishna (2022A3PS0392P)  
- Yash Patil (2022A3PS0437P)  
- Aaryan Saraf (2022A8PS1239P)  

---

## 📜 License  
This project is released under the **MIT License**.  

---

### 🚀 How to Run  
1. Open `.asc` schematic in **LTSpice**.  
2. Run DC, AC, and transient simulations.  
3. Compare results with provided plots.  
4. View extracted layout and verify DRC compliance.  


