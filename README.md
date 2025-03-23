# 🚀 Linear Accelerator Position and PPR Valve Control using STM Microcontroller  

## 📖 Table of Contents  
- [Overview](#-overview)  
- [Technologies Used](#-technologies-used)  
- [Components](#-components)  
- [Features](#-features)  
- [Setup & Installation](#-setup--installation)  
- [License](#-license)  

## 🔍 Overview  
This project involves the design and implementation of control systems for a **linear accelerator** and a **PPR (Pilot-Operated Pressure Relief) valve** using an **STM32F401CB** microcontroller and **STM32CubeIDE**. The system provides real-time motor and valve control with feedback from an encoder and a pressure sensor to ensure high accuracy and stability.  

## 🛠️ Technologies Used  
- **Microcontroller:** STM32F401CB  
- **Software:** STM32CubeIDE  
- **Communication:** RS485  

## 🔩 Components  
### ✅ **Linear Accelerator Position Control**  
- **STM32F401CB** – STM32 microcontroller for control  
- **L16-P Linear Actuator** – Actuator for linear motion  
- **ODrive S1** – Motor driver to control the actuator  
- **AMT21 Encoder** – To provide position feedback  
- **RS485 Module** – For communication with the encoder  
- **External Power Supply (12V)** – To power the actuator and driver  

### ✅ **PPR Valve Control**  
- **STM32F401CB** – STM32 microcontroller for control  
- **28BYJ-48 Stepper Motor** – Stepper motor for valve control  
- **ULN2003A Driver Module** – Driver to control the stepper motor  
- **BMP180** – Pressure sensor to measure pressure levels  

## 🚀 Features  
✅ Real-time motor and valve control using STM32CubeIDE  
✅ High-accuracy position and pressure feedback using RS485 communication  
✅ Optimized response time for smooth and stable operation  

## 🔧 Setup & Installation  
1. **Install STM32CubeIDE** – Download and install from the official ST website.  
2. **Connect the components** according to the circuit diagram.  
3. **Upload the code** using STM32CubeIDE.  
4. **Test the system** – Ensure real-time feedback and control.  

## 📜 License  
This project is open-source under the [MIT License](LICENSE).  
