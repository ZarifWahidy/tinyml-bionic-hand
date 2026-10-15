# Low-Cost TinyML-Driven Bionic Arm

## Project Overview
This Capstone project focuses on developing an accessible, low-cost bionic prosthetic hand controlled by surface electromyography (sEMG) sensors and an embedded TinyML neural network running directly on an ESP32 microcontroller.

By analyzing forearm muscle signals on-device with low latency, the system classifies multi-finger hand gestures (such as Fist, Open Hand, and Pinch) to drive servo motors in a 3D-printed prosthetic hand. The project combines hardware signal acquisition, machine learning, and open-source mechanical design to demonstrate advanced prosthetic control on low-power hardware.

---

## Key Features
- **sEMG Signal Acquisition:** Custom signal conditioning and filtering for forearm muscle activity.
- **On-Device TinyML Inference:** Real-time gesture classification running natively on the ESP32 via Edge Impulse C++ libraries.
- **Servo Motor Actuation:** PWM-driven control for individual finger movements.
- **Open-Source Mechanical Design:** 3D-printable prosthetic hand structure adapted for tendon-driven actuation.
- **Hardware Integration:** Transition from breadboard prototypes to a custom PCB layout.

---

## Repository Structure
```text
├── docs/                 # Schematics, PCB designs, and project documentation
├── firmware/             # ESP32 C++ firmware and TinyML model libraries
├── machine_learning/     # Python scripts for sEMG data collection and model training
├── hardware/             # 3D print STL files and mechanical CAD models
└── README.md             # Project introduction and setup guide
