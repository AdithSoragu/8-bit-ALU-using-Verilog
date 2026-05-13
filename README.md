# 8-bit ALU using Verilog

An **8-bit Arithmetic Logic Unit (ALU)** designed using Verilog HDL and simulated using EDA Playground. This project performs multiple arithmetic and logical operations on 8-bit input data and verifies the results through simulation waveforms.

---

## Project Overview
The Arithmetic Logic Unit (ALU) is the core computational block of processors and digital systems. This project implements an 8-bit ALU capable of executing different arithmetic and logical operations based on control signals. 

### Key Features:
* **Data Width:** 8-bit inputs and outputs.
* **Design Method:** Behavioral modeling in Verilog.
* **Verification:** Tested using testbenches and waveform analysis.

---

## 🛠️ Tools & Technologies
* **Language:** Verilog HDL
* **Simulation:** [EDA Playground](https://www.edaplayground.com/)
* **Simulator Engines:** ModelSim

---

## 🚀 Operations Supported
The ALU performs the following operations based on a selection line (Opcode):

| Operation Type | Functions |
| :--- | :--- |
| **Arithmetic** | Addition, Subtraction, Multiplication, Division |
| **Logical** | AND, OR, XOR, NOT, NAND, NOR |
| **Shifting** | Logical Shift Left, Logical Shift Right |

---

## 📂 How to Run
1.  Clone this repository to your local machine.
2.  Upload the design and testbench files to [EDA Playground](https://www.edaplayground.com/).
3.  Select **Icarus Verilog** or **ModelSim** as the simulator.
4.  Check the "Open EPWave after run" box to view results.
5.  Run the simulation.

Developed as part of the [adithprojects](https://github.com/AdithSoragu/adithprojects) collection.
---
