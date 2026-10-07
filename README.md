# ⚖️ Self-Balancing Robot (Hardware Prototyping)

## 📌 Project Overview
This repository documents the hardware design, component selection, and system integration of a two-wheeled self-balancing robot. The project demonstrates the physical construction of an inverted pendulum system, focusing on precise sensor wiring, power management, and actuator integration.

## 📸 Hardware Showcase
<img width="1927" height="2560" alt="balance_robot" src="https://github.com/user-attachments/assets/6e5a438a-032d-468c-8c43-685b4004d001" />
*(Hướng dẫn: Kéo thả ảnh chụp xe cân bằng của em vào đây giống như lúc làm dự án Drone)*

## 🛠️ Bill of Materials (BOM)

- **Microcontroller:** ESP32 Development Board
- **Inertial Measurement Unit (IMU):** MPU6050 (6-axis accelerometer and gyroscope)
- **Motor Driver:** TB6612FNG Dual DC Motor Driver
- **Actuators:** 2 x GA25 370 DC Gear Motors with Hardware Encoders (280 RPM)
- **Power System:** 3S Li-ion Battery Pack

## ⚙️ Hardware Engineering Highlights
- **Center of Gravity Optimization:** The chassis was designed and physically assembled to ensure a centered mass, significantly reducing the mechanical effort required by the motors to maintain balance.
- **Sensor & Actuator Integration:** Successfully wired the MPU6050 via I2C for accurate tilt angle measurement, synchronized with high-precision GA25 370 encoder motors for real-time torque response.

## 📁 Repository Structure
- `/3D_Models`: Structural components, chassis plates, and motor mounts.
- `/Media`: Assembly photos and testing videos.
