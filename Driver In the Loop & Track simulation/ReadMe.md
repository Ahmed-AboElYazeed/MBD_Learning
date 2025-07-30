# 🚗 Driver-in-the-Loop Simulation – Shell Eco-marathon 2025

This repository documents the design and development of a **Driver-in-the-Loop (DIL) simulation** platform built using **MATLAB & Simulink**, developed for the **Shell Eco-marathon 2025** competition.

> ⚠️ **Note:** Due to competition regulations, the actual simulation files are not included in this repository. However, this README outlines the complete development process and methodology. If you're interested in building a similar project, feel free to contact me directly.

---

## 🧩 Project Overview

The goal of this project is to build a **real-time driver-in-the-loop simulation** that supports:
- Driver training
- Vehicle dynamics validation
- Strategy optimization

The simulation is integrated with real-world track data (elevation, wind, curvature), realistic tire and motor models, and advanced path-tracking controllers.

---

## 🛠️ Tools & Technologies Used

- **MATLAB & Simulink (R2024b)**
- **Simscape Multibody**
- **Magic Formula Tire Model**
- **Google Earth + Elevation API**
- **Custom wind data API**
- **Data visualization & telemetry interfaces**

---

## 📁 System Architecture and Visuals

### 1. Advanced Controller Model

<img width="1614" height="556" alt="1_Model_Advanced_StanlyController" src="https://github.com/user-attachments/assets/c36f8629-7614-4006-bce0-6acd5da5af63" />

### 2. Visualization Blocks

<img width="632" height="581" alt="2_Display   Visualization blocks" src="https://github.com/user-attachments/assets/b4ea76e0-cff4-4b5d-b418-15a30bf8252c" />

### 3. Magic Formula Tire Model

<img width="843" height="437" alt="3_MF" src="https://github.com/user-attachments/assets/217283b5-9698-45c9-8157-86888839fdea" />

### 4. Lateral and Longitudinal Control

<img width="1122" height="602" alt="4_Lat   Long Stanly controllers" src="https://github.com/user-attachments/assets/30ea66c2-41fd-41a7-9b0f-dfd8ed69be6e" />

### 5. Telemetry Output View

<img width="951" height="516" alt="5_Visualization" src="https://github.com/user-attachments/assets/e3fbf876-6fc2-412e-9ae6-7b1ea8e7ffa0" />

### 6. Driver-in-the-Loop Interface

<img width="1920" height="1042" alt="6_Driver veiw (DIL)" src="https://github.com/user-attachments/assets/72d4af87-9818-43b5-b302-2f0a03fca028" />

### 7. Google Earth Elevation Profile

<img width="1920" height="1030" alt="7_Google earth elevation profile" src="https://github.com/user-attachments/assets/6dd1fa7d-92ff-4d05-8643-7995da90cb08" />

### 8. Vehicle Performance Analysis

<img width="1046" height="662" alt="8_Vehicle performance" src="https://github.com/user-attachments/assets/3dadd5f4-7708-4162-b913-035063118131" />

### 9. Speed Profile on Track

<img width="690" height="522" alt="9_velprof on track" src="https://github.com/user-attachments/assets/821cb44a-5d4c-4b78-8783-604a17463cf1" />

### 10. Strategy Comparison Chart

<img width="932" height="657" alt="10_Strategy comparison" src="https://github.com/user-attachments/assets/126aeb75-3ad8-430a-b4b6-90097f834b82" />

---

## 🔍 Additional Engineering Models

### Minimum Curvature Estimation

<img width="1107" height="896" alt="MinCurvature" src="https://github.com/user-attachments/assets/b1389384-8ffa-497b-8c0a-eb354176ad66" />
<img width="1071" height="870" alt="MinCurvature_Path" src="https://github.com/user-attachments/assets/23b84374-58ed-4ab0-8b10-306f24342a21" />

### Motor and Grade Evaluation

<img width="1682" height="607" alt="Model_small_motorSelection" src="https://github.com/user-attachments/assets/fbbfc40c-5233-436c-9522-9498b77b9019" />
<img width="1502" height="903" alt="Motor selection on forword graded track" src="https://github.com/user-attachments/assets/2192a9c2-53ef-4446-9cd0-0d606f8f8cdb" />

### Grade and Wind Data Generation

<img width="1642" height="877" alt="grade generation" src="https://github.com/user-attachments/assets/9530abdb-edfd-4e2a-81d0-572e93ed97af" />
<img width="1920" height="1030" alt="wind data generation API " src="https://github.com/user-attachments/assets/b9c0ea7f-4673-46b6-81e4-255a96fcd65c" />

---

## 🔁 Development Workflow

1. **Track Data Collection**
   - Extracted lat/lon/elevation data using Google Earth and APIs.
   - Generated slope (grade) and wind profiles for the track.

2. **Vehicle Dynamics Modeling**
   - Built a Simulink vehicle model using longitudinal and lateral dynamics.
   - Integrated the Magic Formula tire model for realistic behavior.

3. **Controller Design**
   - Developed Stanley-based path tracking controllers.
   - Generated optimal velocity profiles based on curvature and grade.

4. **Driver-in-the-Loop Integration**
   - Built an interactive simulation cockpit.
   - Enabled real-time telemetry and feedback to the driver.

5. **Visualization & Strategy Evaluation**
   - Analyzed energy usage, velocity trends, and control behavior.
   - Compared strategies to improve efficiency on hilly/windy tracks.

---

## 📬 Contact

If you're a student, researcher, or developer working on a similar competition or simulator and want help recreating or understanding the system, reach out!

**👤 Ahmed AboElyazeed**  
📧 **Email:** [ahmed.abouelyazeed@gmail.com](mailto:aboelyazeed7777@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/ahmedaboelyazeed](https://www.linkedin.com/in/ahmed-aboelyazeed-43ba22231/)

---


