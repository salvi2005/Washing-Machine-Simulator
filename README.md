# Washing-Machine-Simulator-PIC16F877A
A microcontroller-based Washing Machine Simulator using PIC16F877A, written in Embedded C using MPLAB X and simulated in PICSIMLAB.
e# 🧼 Washing Machine Simulator using PIC16F877A

This project simulates a basic washing machine operation using the **PIC16F877A** microcontroller. The embedded C code is written and compiled using **MPLAB X IDE** with the **XC8 compiler**. The logic is tested and simulated using **PICSimLab** on the **PICGenios** board.

## 🧾 Setup Guide

Refer to the [Installation Guide](./Installation_Guide.pdf) for detailed steps to install MPLAB X IDE, XC8 Compiler, and PICSimLab.

## 🔧 Tool Installation Overview

1. Download and install [MPLAB X IDE](https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide).
2. Install the [XC8 Compiler](https://www.microchip.com/en-us/tools-resources/develop/mplab-xc-compilers).
3. Download [PICSimLab](https://sourceforge.net/projects/picsimlab/).

---

## 🛠️ Tools & Technologies Used

- **Microcontroller**: PIC16F877A  
- **Board**: PICGenios  
- **IDE**: MPLAB X IDE  
- **Compiler**: MPLAB XC8 Compiler  
- **Simulator**: PICSimLab

---

## 📂 Folder Structure

washing-machine-simulator/
├── source_files/ # All .c source code files
├── header_files/ # All .h header files
├── README.md # Project overview and instructions


---

## ⚙️ How to Run the Project

### 🧱 Step 1: Open and Build in MPLAB X IDE

1. Open **MPLAB X IDE** and create a new project or import the source and header files.
2. Make sure the **XC8 compiler** is properly installed and selected.
3. Use the **Clean and Build Project** option (hammer icon) to compile the project.
4. This will automatically generate a `.hex` file for simulation.

### 🧪 Step 2: Simulate in PICSimLab

1. Launch **PICSimLab**.
2. Select the **PICGenios** board.
3. Choose the **PIC16F877A** microcontroller.
4. Load the generated `.hex` file (from the `dist` directory of your MPLAB project).
5. Start the simulation and observe washing machine behavior through simulated LEDs or components.

---

## 🎯 Features

- Simulates washing machine stages: Washing, Rinsing, and Spinning.
- Implements time-based transitions using delay logic.
- Visual feedback via LEDs.
- Demonstrates embedded systems design and microcontroller programming.

---

## 📸 Demo

[*A Demonstration Video showing Real-Time working of the Washing Machine Simulator.*
](https://www.youtube.com/watch?v=v5Qme13pObU)
---

## 📑 License

This project is open-source and available under the MIT License.  
You may use or modify it for educational or non-commercial use.

---

## 👩‍💼 Author

**Salvi Kashyap**  
7th semester 4th Year B.Tech Student from Electronics and Communication Branch.

Indira Gandhi Government Engineering College, Sagar(M.P.)
