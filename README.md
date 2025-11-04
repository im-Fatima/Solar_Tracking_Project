# One-Axis Solar Panel Tracker — DSP Course Project

This project implements a **one-axis solar panel tracker** that uses Digital Signal Processing (DSP) techniques to maximize energy capture by continuously aligning the panel with sunlight. It integrates hardware (Arduino UNO, PCA9685 driver, MG996R servo, and LDR sensors) with software algorithms for signal filtering, noise reduction, and real-time control.

---

## 📌 Features
- One-axis rotation with servo + pulley mechanism.  
- DSP-based filtering of LDR sensor readings to reduce noise.  
- Real-time Arduino UNO control with PCA9685 servo driver.  
- Torque and tension calculations for proper servo selection.  
- Documentation: conference paper, video demonstration, CAD visuals, and specifications.  

---

## 📂 Repository Contents
- **`docs/`** — research paper, and conference paper  
- **`Images/`** — contains all the images 
- **`video/`** — working and making of the project

---

## 🔧 Hardware
- **Arduino UNO** microcontroller.  
- **PCA9685 PWM driver**.  
- **MG996R servo motor**.  
- **2× LDRs** for sunlight intensity comparison.  
- **Solar panel** mounted on pulley + string mechanism.  

---

## 🖼️ Project Images

### Hardware Setup
![Hardware](Images/circuitry.jpg)

### Solar Panel on Stand
![Solar Panel on Stand](Images/panel_side_view.jpg)

### Pulley + String Mechanism
![Pulley System](Images/pulley_mechanism.jpg)

### Panel Specifications
![Panel_specifications](Images/Panel_specifications.jpg)
---

## 💻 Firmware
- Reads LDR values.  
- Applies DSP filtering (moving average).  
- Compares east vs west light intensity.  
- Adjusts servo angle to track sunlight.  

---

