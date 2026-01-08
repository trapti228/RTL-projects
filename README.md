# RTL Design Projects 

## Description
This repository contains basic **RTL design projects** implemented using **Verilog HDL**.  
The projects demonstrate the design and verification of **Half Adder** and **Full Adder** using synthesizable RTL code.

## Projects Included
### 1. Half Adder
- Adds two 1-bit binary numbers
- Outputs Sum and Carry
- Implemented using combinational RTL logic

### 2. Full Adder
- Adds three 1-bit binary inputs (A, B, Cin)
- Outputs Sum and Carry-out
- Designed using RTL Verilog

## File Structure
# 4-Bit Adder / Subtractor (Verilog)

This project implements a **4-bit Adder/Subtractor** using **Verilog HDL**.  
The design performs both addition and subtraction using a single arithmetic circuit.

---

## 📌 Functionality

The operation is selected using a control signal:

- `mode = 0` → Addition (`A + B`)
- `mode = 1` → Subtraction (`A - B`)

Subtraction is implemented using **2’s complement** logic.
