# 🌀 BLDC Motor Mathematical Modeling – Trapezoidal Commutation

This project demonstrates the **mathematical modeling of a BLDC motor** using a custom trapezoidal BEMF (Back EMF) approach. It includes detailed Simulink diagrams for modeling rotor speed, EMF profiles, torque calculation, and switching logic.

> ❗ Source files are not shared due to academic and competition restrictions. This documentation outlines the methodology and logic used to build the model for anyone interested in replicating the work.

---

## 📘 Project Scope

- Build a **second-order BLDC model** based on mathematical principles.
- Implement **trapezoidal EMF functions** to simulate switching behavior.
- Simulate real-time rotor dynamics (ω) and sector-based commutation.
- Analyze rotor speed, torque, and BEMF waveform response over time.

---

## 🛠️ Tools Used

- **MATLAB/Simulink**
- **Trapezoidal function modeling**
- **MATLAB Function blocks for BEMF sector logic**
- **Scope analysis for ω (rotor speed) and θ (position)**

---

## 🧩 System Block Diagrams & Simulation Visuals

### 1. Complete Model Structure
<img width="1718" height="663" alt="BLDC mathematical_method 2_main" src="https://github.com/user-attachments/assets/2d0ea820-6ca4-4f93-9e11-83f4fdda8dc6" />

### 2. Model internal Structure
<img width="1577" height="562" alt="BLDC mathematical_method 2_sec" src="https://github.com/user-attachments/assets/340764f6-f3d0-410f-8110-d8731ffc5d73" />

### 3. Trapezoidal BEMF Logic Block
<img width="1371" height="681" alt="BLDC mathematical_method 2_BemfTrap" src="https://github.com/user-attachments/assets/38623439-ff80-42d7-9f33-c0923fc2ca2c" />

### 4. Rotor Speed Equation Section
<img width="1712" height="728" alt="BLDC mathematical_method 2_omega" src="https://github.com/user-attachments/assets/3eb288e3-ddc7-4993-bd24-8b9b7a038e2e" />

### 5. Trapezoidal Function Used
<img width="461" height="343" alt="Trapezoidal function" src="https://github.com/user-attachments/assets/da96ca90-c898-4249-98b4-ebe92550dbef" />

---

## 🧠 Key Modeling Concepts

- **Rotor Dynamics (ω):** Solved via a 2nd order system using moment of inertia, load torque, and back EMF.
- **BEMF (Back EMF):** Modeled as idealized trapezoidal waveforms aligned with rotor position.
- **Commutation Logic:** Sector-based switching determined by rotor angle and lookup tables.
- **Trapezoidal EMF Generation:** Designed using piecewise functions and sector detection.

---

## 🔍 Applications

This modeling approach is useful for:
- Embedded BLDC controller prototyping
- Testing commutation strategies (e.g. 6-step)
- Educational demonstrations of BLDC fundamentals
- Sensorless control algorithm simulation

---

## 📬 Contact

Feel free to contact me if you're building your own BLDC simulation or controller:

**👤 Ahmed AboElyazeed**  
📧 [aboelyazeed7777@gmail.com](mailto:aboelyazeed7777@gmail.com)  
🔗 [linkedin.com/in/ahmedaboelyazeed](https://www.linkedin.com/in/ahmed-aboelyazeed-43ba22231/)

---
