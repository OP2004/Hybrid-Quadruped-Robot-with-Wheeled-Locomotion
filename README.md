# Hybrid Quadruped Robot with Wheeled Locomotion for Terrain Navigation

## Project Overview

This project presents the design and development of a **Hybrid Quadruped Robot** integrated with **Wheeled Locomotion** for efficient multi-terrain navigation. The system combines the stability and adaptability of legged locomotion with the speed and energy efficiency of wheeled motion.

The robot is capable of seamlessly switching between walking and rolling modes depending on terrain conditions, enabling robust performance across smooth, uneven, and obstacle-rich environments.

---

## Problem Statement

Traditional wheeled robots are efficient on flat surfaces but struggle on rough terrain. Conversely, quadruped robots offer superior adaptability but suffer from slower speeds and higher energy consumption.

This project addresses these limitations by developing a hybrid leg–wheel robotic platform capable of:
- Seamless locomotion mode switching
- Stable gait transitions
- Improved energy efficiency
- Enhanced terrain adaptability

---

## System Architecture

The hybrid quadruped robot consists of:

- **Mechanical System**
  - Four articulated legs
  - Integrated wheel modules at leg end-effectors
  - Modular chassis design

- **Electronics**
  - Microcontroller-based embedded control system
  - Motor drivers for servo and wheel actuation
  - Rechargeable battery power supply
  - Voltage regulation system

- **Sensors**
  - IMU (Inertial Measurement Unit)
  - Ultrasonic sensors
  - Encoders
  - Camera module (ESP32-CAM)

- **Software Stack**
  - ROS (Robot Operating System)
  - Gazebo simulation
  - RViz visualization
  - Embedded C / Arduino programming

---

## ⚙️ Working Principle

The robot operates in three locomotion modes:

1. **Walking Mode**
   - Gait-based leg movement (crawl / trot)
   - Used for uneven and obstacle-filled terrain

2. **Wheeled Mode**
   - Continuous rolling motion
   - Used for smooth, flat surfaces
   - Improved speed and energy efficiency

3. **Hybrid Mode**
   - Adaptive switching between leg and wheel
   - Controlled via terrain sensing and control algorithms

The system uses layered control architecture:

- Low-Level: Joint and wheel actuation  
- Mid-Level: Gait planning & mode switching  
- High-Level: Path planning & terrain analysis  

---

## Methodology

1. Problem identification & requirement analysis  
2. CAD modeling (Fusion 360 / SolidWorks)  
3. Hybrid leg-wheel integration design  
4. Control algorithm development  
5. Sensor integration  
6. ROS-based simulation validation  
7. Prototype development  
8. Testing & performance evaluation  

---

## Technologies Used

- Robotics & Automation Principles  
- CAD Modeling (Fusion 360)  
- ROS (Robot Operating System)  
- Gazebo Simulation  
- RViz Visualization  
- Arduino / Embedded C  
- ESP32-CAM  
- Inverse Kinematics  
- Gait Planning Algorithms  

---

## Results

- Stable locomotion over uneven terrain  
- Efficient rolling on flat surfaces  
- Seamless transition between walking and wheeled modes  
- Improved energy utilization in drive mode  
- Successful simulation validation before hardware deployment  

---

## Applications

- Search and Rescue Operations  
- Military Surveillance  
- Industrial Inspection  
- Agricultural Monitoring  
- Planetary Exploration  
- Autonomous Mobile Robotics  

---

## Innovation & Contribution

This project introduces a coordinated hybrid locomotion framework integrating:

- Leg-wheel mechanical architecture  
- Adaptive locomotion switching  
- Simulation-first validation workflow  
- Embedded real-time control integration  

The system enhances versatility while maintaining mechanical stability and energy efficiency.

---

## Future Scope

- AI-based terrain classification  
- SLAM-based autonomous navigation  
- Computer vision obstacle detection  
- Energy optimization algorithms  
- Mobile app-based remote control  
- Fully autonomous hybrid robotic platform  
## 📁 Repository Structure

---
