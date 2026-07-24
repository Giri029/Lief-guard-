# 🚀 RUSHOUR 2026 - National Engineering Hackathon

> **24-Hour National Engineering Challenge**
>
> **Theme:** Innovate • Build • Solve • Impact

---

## 🛡️ LiefGuard IoT: Intelligent Fatigue Prevention & Adaptive Recovery System

### 👥 Team Members
1) Giri G (team leader)
2) Athish RK
3) K Mohit Sai
4) Johen Giovannii
5) Dhashvanth V
6) Praveen kumar S

> **A closed-loop IoT & Cloud ecosystem bridging real-time biomechanical strain monitoring with automated nutritional recovery.**

---

## 📌 Project Overview

**LiefGuard IoT** is a smart, cloud-connected fitness and safety ecosystem designed to protect strength athletes from overtraining, central nervous system (CNS) burnout, and catastrophic biomechanical injury (ego lifting). By combining real-time hardware motion tracking on the gym floor with an automated, frictionless nutrition logger, LiefGuard ensures that training intensity is constantly balanced with adequate physical recovery.

---

## 🚨 Problem Statement

In resistance training and high-intensity weightlifting, athletes face three critical failure points that traditional wearables and apps completely ignore:

1. **Biomechanical Strain & Ego Lifting Risks:** Existing smartwatches only track passive metrics like daily step counts and basic pulse. They fail to measure explosive lifting velocity, angular instability, or form breakdown. Pushing through severe fatigue leads to muscle tears and joint failure.
2. **The "Muscle vs. Tendon" Recovery Gap:** While muscles adapt rapidly to heavy loads, tendons and ligaments adapt much slower. Athletes using high-stimulant pre-workouts often lose pain feedback, pushing heavy loads that exceed tendon tensile limits.
3. **High-Friction Nutrition Tracking:** Manual calorie/macro tracking apps require tedious text entry, leading over 70% of athletes to abandon diet tracking altogether. Without accurate nutrition, cellular repair fails.

---

## 💡 Our Solution

LiefGuard connects the gym floor directly to the kitchen through a two-node closed-loop architecture:

### 1. The Hardware Edge Node (Wearable / Desk Hub)
* **ESP32 Microcontroller:** The central processor handling local edge computations and cloud wireless streaming.
* **MPU6050 Accelerometer & Gyroscope:** Tracks real-time lifting acceleration, movement symmetry, and velocity loss to catch form breakdown mid-rep.
* **MAX30102 Heart Rate Sensor:** Measures cardiovascular strain and pulse wave density to compute real-time exertion.
* **Local Safety Warnings:** An onboard **OLED display** shows immediate exertion states (`OPTIMAL` vs `OVERTRAINED`), while an active **Piezo Buzzer** sounds an instant auditory warning when form breaks down or safe acceleration thresholds are breached.
* **RFID Module (RC522):** Enables tap-to-log frictionless meal logging right from the device.

### 2. The Cloud & Web Ecosystem
* **Firebase Realtime Database:** Low-latency cloud synchronization streaming sensor packets from the hardware directly to the cloud dashboard.
* **Adaptive Nutrition Algorithm:** Dynamically scales target macronutrient and calorie goals based on live daily training intensity (e.g., automatically adjusting targets on heavy leg days).
* **Interactive Dashboard:** A modern web interface displaying real-time fatigue gauges, target completion bars, and workout logs.

---

## 🏗️ System Architecture & Workflow
