# 📡 50Ω Microstrip Line Design using Altium & QUCS

## 📌 Project Overview
This project demonstrates the complete RF workflow for designing and validating a **50Ω microstrip transmission line**.

The workflow includes:
- PCB layout design in Altium Designer
- Impedance calculation using TXLine (stripline calculator)
- S-parameter (S11) simulation using QUCS
- Reflection and return loss validation

This project focuses on controlled impedance design for RF and high-speed PCB applications.

---

## 🎯 Design Objective
- Design a 50Ω microstrip transmission line
- Achieve proper impedance matching
- Minimize reflection coefficient (S11)
- Validate analytical results with simulation

---

## 🛠 Tools Used
- **Altium Designer** – PCB layout and stack-up definition
- **TXLine** – Impedance calculation
- **QUCS (Quite Universal Circuit Simulator)** – S-parameter simulation

---

## 📐 Design Parameters

| Parameter              | Value (Example) |
|------------------------|-----------------|
| Substrate Material     | FR4             |
| Dielectric Constant    | 4.3             |
| Substrate Height (H)   | 1.6 mm          |
| Copper Thickness       | 35 µm           |
| Target Impedance       | 50 Ω            |

> Note: Exact trace width was calculated using TXLine to achieve 50Ω impedance.

---

## 🧮 Impedance Calculation (TXLine)
The required trace width was calculated using TXLine based on:
- Dielectric constant
- Substrate height
- Copper thickness

The calculated width ensures a characteristic impedance of approximately 50Ω.

---

## 📊 S-Parameter Simulation (QUCS)

Simulation steps:
1. Microstrip modeled as transmission line element
2. Port impedance set to 50Ω
3. Frequency sweep performed
4. S11 parameter observed

### Key Result:
- Low S11 at target frequency
- Good impedance matching
- Minimal reflection

---

## 📈 Understanding S11

S11 (Return Loss) indicates how much power is reflected back from the transmission line.

- S11 ≈ 0 dB → High reflection (Bad matching)
- S11 < -10 dB → Acceptable matching
- S11 < -20 dB → Very good matching

Lower S11 means better impedance matching.

---

## 🧠 Learning Outcomes

- Controlled impedance PCB design
- Stack-up planning for RF
- Transmission line theory application
- Reflection coefficient analysis
- Practical S-parameter simulation workflow

---

## 📂 Repository Structure

---

## 🚀 Future Improvements

- Compare microstrip vs stripline performance
- Perform frequency-dependent loss analysis
- Include TDR simulation
- Extend to differential pair design

---

## 📬 Author
Harsh Saini  
Electronics & Communication Engineer  
Focused on RF, SI/PI, and High-Speed PCB Design
