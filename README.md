# 8-to-1 Multiplexer using Verilog HDL

## 📌 Project Overview

This project implements an **8-to-1 Multiplexer (MUX)** using Verilog HDL. The design selects one of eight input signals and transfers the selected signal to a single output using three select lines.

## 🔧 Modeling Techniques

* Behavioral Modeling
* Data Flow Modeling
* Gate-Level Modeling

## ⚙️ Inputs and Outputs

| Signal     | Description       |
| ---------- | ----------------- |
| I0–I7      | Eight data inputs |
| S2, S1, S0 | Select lines      |
| Y          | Output            |

## 📊 Truth Table

| S2 | S1 | S0 | Output |
| -- | -- | -- | ------ |
| 0  | 0  | 0  | I0     |
| 0  | 0  | 1  | I1     |
| 0  | 1  | 0  | I2     |
| 0  | 1  | 1  | I3     |
| 1  | 0  | 0  | I4     |
| 1  | 0  | 1  | I5     |
| 1  | 1  | 0  | I6     |
| 1  | 1  | 1  | I7     |

## 🔲 Block Diagram

<img width="1774" height="887" alt="ChatGPT Image Sep 30, 2026, 03_49_42 PM" src="https://github.com/user-attachments/assets/22958ffa-683e-4599-a807-24f4b3d0ccce" />

## 💻 Verilog Code

### Behavioral Modeling

<img width="1215" height="679" alt="WhatsApp Image 2026-06-09 at 11 46 10 AM (4)" src="https://github.com/user-attachments/assets/92e3f4cc-f32d-488e-b5ae-80be791742bf" />

### Data Flow Modeling

<img width="1217" height="685" alt="WhatsApp Image 2026-06-09 at 11 46 10 AM (1)" src="https://github.com/user-attachments/assets/413440c3-314c-44b3-9c5d-44ee4286840d" />


### Gate-Level Modeling

<img width="1215" height="692" alt="WhatsApp Image 2026-06-09 at 11 46 10 AM (3)" src="https://github.com/user-attachments/assets/8735ddd9-bc4b-4180-a17c-3659219a7ea7" />


## 📈 Simulation / Waveform

<img width="1214" height="701" alt="WhatsApp Image 2026-06-09 at 11 46 10 AM" src="https://github.com/user-attachments/assets/8f90386c-e91c-4fd3-bfeb-a190d7561880" />


## 🛠️ Tools Used

* Verilog HDL
* Vivado
 
## 🎯 Learning Outcome

This project demonstrates the implementation of an **8-to-1 Multiplexer** using different Verilog HDL modeling techniques and provides practical understanding of **combinational logic, multiplexing, and RTL design**.
