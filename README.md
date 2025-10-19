# Fully Automatic Washing Machine Controller (Verilog HDL)

This repository contains the complete design, Verilog HDL code, simulation testbenches, and documentation for a **Fully Automatic Washing Machine Controller** project. The goal is to model and simulate the digital control logic of a modern washing machine using modular, synthesizable Verilog, with a focus on mastering finite state machine (FSM) design, timing control, and hardware simulation.

## Features
- Modular Verilog implementation of the washing machine controller
- Clear FSM-based control logic for all washing cycles (fill, wash, rinse, spin, done)
- Parameterized timing for each operation
- Simulated sensor and actuator interfaces
- Comprehensive testbench for functional verification
- Waveform outputs for easy debugging and demonstration

## Project Structure
- `src/` — Verilog source files (FSM, timer, IO modules)
- `tb/` — Testbench files and simulation scripts
- `docs/` — Block diagrams, FSM state diagrams, and project report
- `waveforms/` — Example simulation outputs (VCD files, screenshots)

## Getting Started
1. Clone the repository.
2. Open the Verilog files in your preferred HDL editor (e.g., VS Code).
3. Run simulations using Icarus Verilog, ModelSim, or EDA Playground.
4. View waveforms with GTKWave or your preferred viewer.

## Learning Outcomes
- Mastery of FSM and sequential logic design in Verilog
- Experience with modular HDL coding and simulation
- Practical understanding of digital system integration and verification

***

*This project was developed as part of an academic course to demonstrate practical digital design skills using Verilog HDL. For questions or collaboration, please open an issue or contact the contributors.*
