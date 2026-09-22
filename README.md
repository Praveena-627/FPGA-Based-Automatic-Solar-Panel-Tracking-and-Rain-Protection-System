# FPGA-Based Automatic Solar Panel Tracking and Rain Protection System

## 📌 Project Overview

This project implements an **FPGA-based automatic solar panel tracking system** that continuously adjusts the position of a solar panel according to the direction of maximum sunlight. LDR sensors are used to detect light intensity, while servo motors rotate and tilt the panel. The system also includes rain detection and protective positioning.

## 🎯 Objectives

- Automatically track the direction of maximum sunlight.
- Increase the amount of sunlight received by the solar panel.
- Control panel movement using an FPGA.
- Implement the control logic using **Verilog HDL**.
- Detect rain and move the panel to a protective position.
- Control an automatic wiper during rainy conditions.

## 🧩 Components Used

- FPGA Board – **EDGE Artix-7**
- Solar Panel
- LDR Sensors
- Servo Motors
- Rain Sensor
- Wiper Mechanism
- Power Supply
- Connecting Wires

## ⚙️ Working Principle

The LDR sensors measure the intensity of sunlight from different directions. The FPGA receives the sensor values and compares them.

- If the left-side LDR receives more light, the panel rotates left.
- If the right-side LDR receives more light, the panel rotates right.
- If the upper-side LDR receives more light, the panel tilts upward.
- If the lower-side LDR receives more light, the panel tilts downward.
- When the light difference is within a defined range, the panel remains stationary
