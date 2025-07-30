# ⚙️ Shell Eco-marathon 2025 – Electronic Control Board Development

This repository documents the full design, development, and testing of the custom **Electronic Control Unit (ECU)** and **Motor Controller Board** used in the **Shell Eco-marathon 2025** vehicle.

> 🛑 **Note**: PCB design files and schematics are not included due to competition confidentiality. However, the process, architecture, and testing procedures are described here for educational and collaboration purposes.

---

## 📌 Project Overview

The control system consists of a custom-designed PCB used as the **BLDC Motor Controller** and **Vehicle Control Unit (VCU)**. The goal was to build a compact, reliable, and competition-grade controller from scratch — optimized for the needs of an electric prototype vehicle.

---

## 🛠️ Tools & Technologies

- **KiCAD** for PCB design
- **ESP32 microcontroller**
- **IRF540N MOSFETs** for motor drive
- **Optocouplers** for isolation
- **Hall sensors** for rotor position feedback
- **Custom low-voltage logic & high-voltage switching**
- **12V DC power bench testing**

---

## 🖼️ Development Gallery

### ✅ Finalized Control Board
![0_shell eco marathon 2025_final board](https://github.com/user-attachments/assets/ecbda0be-0f4a-408d-953f-43263413847d)

### ⚡ BLDC Motor Controller PCB Design
<img width="1368" height="829" alt="E_Rally BLDC electronic speed control board PCB design" src="https://github.com/user-attachments/assets/f2b686a2-cd20-460b-bfe0-5d07ffd32400" />

### 🔧 PCB Bench Testing with 12V Supply
![Home made PCB testing with 12v power supply](https://github.com/user-attachments/assets/0c5e148c-90ba-4250-a7da-f07a52dab87f)

### 🔌 Motor Controller Board
![MOTOR controller PCB](https://github.com/user-attachments/assets/e585b730-d18f-43b8-9e92-ba3069e37d1e)

### 🔍 VCU Commutation + LED Feedback Test
![VCU commutation_Led test](https://github.com/user-attachments/assets/d91eb47e-e24e-4f1b-9707-9d0a87f75601)

### 🧪 Final PCB Bench Testing
![final SEM 2025 PCB_bench testing](https://github.com/user-attachments/assets/4a7a5686-b71d-467a-8fab-f50fbcfbbd22)

### 🚗 Assembled PCB + Motor Setup
![shell eco marathon 2025_final board and motor](https://github.com/user-attachments/assets/7f23320d-9cb3-439a-acb4-3b8e32199300)

---

## 💡 Key Features

- ✅ Three-phase BLDC control using Hall sensors
- ✅ Safe isolation between low-voltage and high-side MOSFETs
- ✅ Multiple test phases: controller-only, motor-only, and full integration
- ✅ Real-world bench testing with load simulation and manual debugging

---

## 📬 Contact

Feel free to reach out if you're building a similar motor controller or ECU for electric vehicle competitions:

**👤 Ahmed AboElyazeed**  
📧 [ahmed.abouelyazeed@gmail.com](mailto:aboelyazeed7777@gmail.com)  
🔗 [linkedin.com/in/ahmedaboelyazeed](https://www.linkedin.com/in/ahmed-aboelyazeed-43ba22231/)

---

## 🙏 Acknowledgements

This board was developed as part of the **Helwan Racing Team**’s participation in the **Shell Eco-marathon 2025**. Special thanks to my team, faculty mentors, and technical reviewers for their continuous support.
