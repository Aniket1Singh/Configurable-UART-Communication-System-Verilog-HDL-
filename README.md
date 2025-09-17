UART Controller in Verilog
Overview

This project implements a Universal Asynchronous Receiver/Transmitter (UART) in Verilog HDL. The design includes a transmitter, receiver, baud rate generator, and a top-level controller. A dedicated testbench is provided to validate the functionality.

The goal of this project is to provide a modular and easy-to-understand UART design that can be reused for FPGA/ASIC projects or as a reference for learning digital design concepts.

Features

Baud rate generator with configurable parameters

UART transmitter (TX) with start/stop bit handling

UART receiver (RX) with synchronization and data recovery

Top-level UART controller to integrate all modules

Testbench for functional verification

Modular and parameterized design for flexibility

File Structure

baudRateGenerator_stripped.v – Baud rate generator module

defines_stripped.v – Project constants and parameters

uart_tx_controller_stripped.v – Transmitter logic

uart_rx_controller_stripped.v – Receiver logic

uart_controller_stripped.v – Top-level UART integration

UART_TestBench_stripped.v – Testbench for simulation

Tools & Environment

HDL: Verilog

Simulation: ModelSim / Vivado / Quartus

Target Platform: FPGA (can also be adapted for ASIC flow)

Applications

FPGA ↔ PC serial communication

Microcontroller ↔ FPGA data exchange

Embedded systems prototyping

Digital design and HDL learning resource
