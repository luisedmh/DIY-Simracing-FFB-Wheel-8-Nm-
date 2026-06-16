# 🏁 DIY Simracing FFB Wheel (8 Nm)

This project consists of the design, programming, and manufacturing of a custom **Force Feedback (FFB) racing wheel delivering up to 8 Nm of torque**, built entirely from scratch (DIY).

The system emulates a high-end commercial direct-drive or belt-driven base by processing real-time telemetry data from racing simulators via a microcontroller, translating it into physical force through an industrial motor.

---

## 🚀 Key Features

* **High Performance:** Delivers up to **8 Nm of torque** (comparable to mid-to-high-end commercial wheel bases).
* **Plug & Play:** Recognized natively by Windows and simulators (Assetto Corsa, iRacing, rFactor, etc.) as a standard gaming device.
* **High Precision:** Precise angle tracking achieved through a high-resolution optical/magnetic encoder.
* **Robust Structure:** Chasis and internal mechanical components are 100% 3D printed, optimized to withstand high mechanical stress and torque ripple.

---

## 🛠️ Components & Technologies

### Hardware & Electronics
* **Microcontroller:** Arduino Leonardo (ATmega32U4) utilizing native USB HID support.
* **Actuator:** High-torque industrial Direct Current (DC) motor.
* **Power Driver:** [Specify model, e.g., BTS7960 / Cytron] to safely manage high current delivery to the motor.
* **Encoder:** [Specify model or PPR, e.g., 600 PPR optical encoder] for precise steering angle feedback.
* **Power Supply Unit (PSU):** [Specify voltage/amperage, e.g., 24V 15A].

### Software & Firmware
* **Language:** C++ / Arduino IDE.
* **Key Libraries:** [Specify if you used any, e.g., EMC Lite, WheelConfig, or a custom HID library].

---

## 📐 Mechanical Design & Manufacturing

All structural and aesthetic parts were 3D modeled and manufactured using **FDM (Fused Deposition Modeling) 3D printing**.
* **Materials Used:** [e.g., PLA+ / PETG / ABS] selected for high impact and torsional resistance.
* **Slicing Optimization:** Applied custom infill densities and wall perimeters on high-stress areas (such as motor mounts and main shaft bearings).

---

## 🔧 Installation & Setup

1. **Wiring:** Follow the wiring diagram provided in the `/hardware` folder to connect the encoder and power driver to the Arduino.
2. **Firmware:** Flash the source code located in `/firmware` using the Arduino IDE.
3. **Calibration:** Plug in the USB, open your preferred simulator, and calibrate the steering lock (supports up to 900°).

---

## 📸 Gallery & Demonstration

*(Pro-tip: Add actual photos of your build and a GIF or YouTube link showing the Force Feedback working in-game).*

| Front View | Internal Mechanism |
| :---: | :---: |
| ![Front View](https://via.placeholder.com/400x300) | ![Mechanism](https://via.placeholder.com/400x300) |

---

## 💡 Skills Demonstrated in this Project
* **Embedded Systems:** Microcontroller programming and custom USB HID configuration.
* **Power Electronics:** DC motor control using PWM signals and high-current driver stages.
* **Mechanical Engineering & Design:** 3D modeling, mechanical tolerances, and additive manufacturing.
* **Problem Solving:** Tuning control loops to match real-time physics engine telemetry.
