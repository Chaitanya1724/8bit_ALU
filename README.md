# 8-bit Arithmetic Logic Unit (ALU)

## 📌 Problem Statement
Design and implement an **8-bit Arithmetic Logic Unit (ALU)** using Verilog HDL.  
The ALU should perform a set of arithmetic and logical operations on two 8-bit operands.  
Simulation of the design is carried out using an **EDA tool** to verify functionality and correctness.

---

## ⚙️ Features
- **Arithmetic Operations**: Addition, Subtraction, Increment, Decrement
- **Logical Operations**: AND, OR, XOR, NOT
- **Shift Operations**: Left Shift, Right Shift
- **Comparison**: Equal, Greater, Less
- **Status Flags**:
  - Zero flag
  - Carry/Overflow flag

---

## 📂 Project Structure
```
8bit_ALU/
│── alu.v             # Verilog code for ALU
│── alu_tb.v          # Testbench for simulation
│── results/          # Simulation results (waveforms, logs)
│── README.md         # Project documentation
```

---

## ▶️ How to Run

### Using EDA Tool
1. Open the **EDA tool** (ModelSim / Xilinx ISE / Vivado / any preferred tool).
2. Add `alu.v` (design file) and `alu_tb.v` (testbench file) to the project.
3. Run behavioral simulation to verify correctness.
4. View simulation waveforms for different ALU operations.

---

## 📊 Results
- **Functional Verification**: All specified operations successfully simulated.
- **Waveforms**: Output confirms expected results for each operation.
- **STA**: Verified using the EDA tool, ensuring timing correctness.

---

## 🔮 Future Enhancements
- Add multiplication and division operations.
- Extend ALU to 16-bit or 32-bit.
- Optimize the design for area and power during synthesis.
- Integrate with a simple CPU datapath for complete processor design.

---

## 👨‍💻 Author
- Project by **[Your Name]**  
- Domain: **VLSI / Digital Design**  
- Tools Used: **Verilog, EDA Tool (for simulation & STA)**

