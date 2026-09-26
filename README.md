# 4-bit ALU Using Verilog HDL

## Project Overview

This project implements a 4-bit Arithmetic Logic Unit (ALU) using Verilog Hardware Description Language (HDL).

The ALU is a fundamental component of a processor and performs arithmetic and logical operations on binary data.

## Features

The designed 4-bit ALU supports the following operations:

| ALU Select | Operation |
|------------|-----------|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | XOR |
| 101 | NOT |
| 110 | Left Shift |
| 111 | Right Shift |

## Inputs

- `A` – 4-bit input
- `B` – 4-bit input
- `ALU_Sel` – 3-bit operation selection

## Outputs

- `Result` – 4-bit ALU result
- `Carry` – Carry output
- `Zero` – Indicates whether the result is zero

## Project Structure

```text
4-bit-ALU-Verilog/
│
├── README.md
├── alu_4bit.v
└── alu_4bit_tb.v
