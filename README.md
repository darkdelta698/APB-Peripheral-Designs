# APB Peripheral Designs

This repository contains Verilog RTL implementations of basic peripherals interfaced through the AMBA Advanced Peripheral Bus (APB) protocol.

The objective is to explore APB-based peripheral interfacing, RTL design, and functional verification.

## Designs Included

### 1. APB Adder
- APB slave interface for an arithmetic adder.
- Accepts input operands through memory-mapped registers.
- Performs addition and provides the result through the APB interface.
- Includes a testbench for functional verification.

### 2. APB 4-bit ALU
- APB slave interface integrated with a 4-bit Arithmetic Logic Unit.
- Supports arithmetic and logical operations.
- Uses memory-mapped registers for operand and operation selection.
- Includes a testbench to verify the ALU functionality.

## Technologies Used
- Verilog HDL
- AMBA APB Protocol
- RTL Design
- Functional Simulation and Verification

## Tools
- Vivado
- [Add your simulation tool here]

## Purpose
These implementations were developed to strengthen my understanding of RTL design, bus protocols, and peripheral interfacing.
