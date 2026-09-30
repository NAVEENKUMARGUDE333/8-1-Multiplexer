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

<!-- Add your block diagram here -->

![8-to-1 MUX Block Diagram](images/block_diagram.png)

## 📐 Circuit Diagram

<!-- Add your circuit diagram here -->

![8-to-1 MUX Circuit Diagram](images/circuit_diagram.png)

## 💻 Verilog Code

### Behavioral Modeling

<!-- Add Behavioral Modeling screenshot here -->

![Behavioral Modeling](images/behavioral.png)

### Data Flow Modeling

<!-- Add Data Flow Modeling screenshot here -->

![Data Flow Modeling](images/dataflow.png)

### Gate-Level Modeling

<!-- Add Gate-Level Modeling screenshot here -->

![Gate-Level Modeling](images/gatelevel.png)

## 📈 Simulation / Waveform

<!-- Add simulation waveform here -->

![Simulation Waveform](images/waveform.png)

## 🛠️ Tools Used

* Verilog HDL
* Vivado / ModelSim / EDA Playground
* Digital Logic Design

## 🎯 Learning Outcome

This project demonstrates the implementation of an **8-to-1 Multiplexer** using different Verilog HDL modeling techniques and provides practical understanding of **combinational logic, multiplexing, and RTL design**.

## 👨‍💻 Author

**Naveen Kumar Gude**

