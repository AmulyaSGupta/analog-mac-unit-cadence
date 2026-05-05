# Analog MAC Unit Design using CMOS (Cadence Virtuoso)

## 📌 Overview
This project presents the design and simulation of a MAC (Multiplier and Accumulator) unit using CMOS technology in Cadence Virtuoso.

The design integrates fundamental building blocks such as adders, multipliers, registers, and flip-flops to perform multiplication and accumulation operations.

---

## ⚙️ Tools Used
- Cadence Virtuoso
- CMOS Technology

---

## 🧠 Design Components
- 8-bit Adder  
- 4×4 Multiplier  
- 8-bit Register  
- D Flip-Flop (Transmission Gate Based)

---

## 🔄 Working Principle
The MAC unit performs the operation:

**Output = ∑ (Ai × Bi)**

- Multiplier generates product  
- Adder accumulates result  
- Register stores intermediate values  

---

## 📊 Performance
- Propagation Delay: ~949 ps  
- Power Consumption: ~104 nW  

---

## 🚀 Future Scope
- Layout design (DRC & LVS)  
- Higher bit-width MAC implementation  
- Optimization for power and speed
## 🖼️ Design Implementation

---

### MAC Unit Schematic
![MAC](images/mac_schematic.png)

### Output Waveform
![Waveform](images/waveform1.png)
