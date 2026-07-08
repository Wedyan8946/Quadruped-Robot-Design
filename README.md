# 🐾 Quadruped Robot Design Project

Welcome to my first robotics project! This repository contains the 3D mechanical design of an 8-DOF (Degrees of Freedom) quadruped robot dog. The model is designed to achieve optimal weight distribution and stable locomotion.

---

## 🛠️ Mechanical Design Features

* Robot Chassis: Designed as a solid rectangular platform to provide maximum surface area, balancing the internal electronic components and centering the mass.
* Leg Mechanism: Symmetrical 2-link leg structure per leg (Upper and Lower leg links) that accurately simulates natural animal hip and knee joints.
* Degrees of Freedom (DOF): Symmetrical 2-DOF per leg, leading to an overall 8-DOF system powered by 8 micro servo motors.
* Stable Footwear: Each leg ends with a sphere-capped foot to ensure steady friction and prevent slipping during movement.
* Stability & Center of Gravity: The solid rectangular chassis ensures that the electronic components (battery and microcontroller) are balanced centrally, keeping the Center of Mass (CoM) perfectly stable in the middle of the 4 legs.
* Proposed Gait: The robot is planned to utilize a "Trot Gait" or dynamic "Walk Gait", coordinated via inverse kinematics to maintain static stability during locomotion.
* Expected Mechanical Challenges: Key anticipated challenges include potential backlash in the servo motor gears over time, and managing structural vibrations at high joint speeds, which can be mitigated by optimizing loop delays.
---

## 📐 Mathematical Calculations & Report

> 📄 Note for Evaluators: 
> All detailed mechanical calculations, including total weight forces ($F_g$), joint torque estimations ($T$), and mathematical models, have been compiled into a dedicated PDF Report attached in the files section above. 

---

## 📸 Project Status
- [x] Symmetrical 3D CAD modeling in Tinkercad.
- [x] Assembly and alignment of the 4 legs.
- [x] Uploading the detailed PDF analysis report.
- [x] Writing the simulation code for the servo movements.
