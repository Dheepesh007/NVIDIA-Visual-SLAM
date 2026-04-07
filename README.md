# 🧭 NVIDIA Visual SLAM (Pose Update)

## 🧠 Overview

This project demonstrates a basic concept of Visual SLAM (Simultaneous Localization and Mapping). It calculates the **updated robot pose** by adding motion displacement to the previous position.

This concept is widely used in NVIDIA-powered robotics and autonomous systems for real-time navigation.

---

## 🎯 Objective

To compute the updated robot pose using:

New Pose = Previous Pose + Motion

---

## 📊 Dataset Used

* TUM RGB-D Dataset
  🔗 https://vision.in.tum.de/data/datasets/rgbd-dataset

Used for SLAM and visual odometry research.

---

## ⚙️ Implementation

* Language: Python
* Platform: Google Colab / VS Code
* Concept: Pose Update (Vector Addition)

---

## 🧮 Example

* Previous Pose = (2, 3)
* Motion = (0.4, 0.6)

**Output:**
New Pose = (2.4, 3.6)

---

## 🏭 Industry Application

Used in:

* Autonomous robots
* Self-driving cars
* Drone navigation

---

## ▶️ How to Run

1. Open in Google Colab or VS Code
2. Run the Python script
3. Input previous pose and motion
4. Get updated pose

---

## 📌 Output

Previous Pose: (2, 3)
Motion: (0.4, 0.6)
New Pose: (2.4, 3.6)

---

## ✅ Result

The robot's new pose is successfully computed as **(2.4, 3.6)** using motion update.
