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
| Arduino UNO | PCA9685 Driver | MG996R Servo |
|-------------|----------------|--------------|
| ![Arduino UNO]([assets/images/arduino_r3.jpg](https://electrobes.com/wp-content/uploads/2019/10/arduino-uno-r3-smd-board-cable-for-arduino-uno-at-best-price-in-pakistan.jpg?v=1695312743)) | ![PCA9685](assets/images/pca9685.jpg) | ![Servo](assets/images/servo_mg996r.jpg) |

### Solar Panel on Stand
![Solar Panel on Stand](assets/images/panel_stand.jpg)

### Pulley + String Mechanism
![Pulley System](assets/images/pulley_mechanism.jpg)

### LDR Arrangement
![Two LDRs](assets/images/ldr_setup.jpg)
---

## 💻 Firmware
- Reads LDR values.  
- Applies DSP filtering (moving average).  
- Compares east vs west light intensity.  
- Adjusts servo angle to track sunlight.  

---

