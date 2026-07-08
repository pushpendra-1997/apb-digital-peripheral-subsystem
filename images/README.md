# APB-Based Digital Peripheral Subsystem

Design and implementation of a modular digital peripheral subsystem for embedded Systems-on-Chip (SoCs) using Verilog HDL.

---

## Overview

Modern embedded SoCs integrate multiple reusable digital peripherals such as GPIO controllers, timers, PWM generators, and interrupt controllers. These peripherals communicate with the embedded processor through a standard bus interface.

This project focuses on the design and implementation of a modular APB-based Digital Peripheral Subsystem using synthesizable Verilog HDL while following an industry-style RTL design methodology, including architecture definition, functional verification, RTL synthesis, and technical documentation.

---

## Project Objectives

- Design reusable digital IP blocks using synthesizable Verilog HDL.
- Implement an AMBA APB-compliant peripheral subsystem for embedded SoCs.
- Develop modular and parameterized RTL suitable for IP reuse.
- Perform functional verification through simulation.
- Perform RTL synthesis using open-source EDA tools.
- Maintain structured project documentation following an industry-oriented development workflow.

---

## Digital IP Blocks

The subsystem consists of the following reusable digital IPs:

- APB Slave Interface
- GPIO Controller
- Programmable Timer
- PWM Generator
- Interrupt Controller

---

## System Architecture

```
                     Embedded Processor
                             │
                      APB Master Interface
                             │
                    -----------------------
                             │
                     APB Slave Interface
                             │
        ---------------------------------------------
        │             │            │               │
      GPIO         Timer         PWM      Interrupt Controller
```

---

## RTL Design Flow

```
Requirement Analysis
        ↓
Architecture Specification
        ↓
RTL Design (Verilog HDL)
        ↓
Functional Verification
        ↓
RTL Synthesis (Yosys)
        ↓
Documentation
```

---

## Development Environment

| Category | Tools |
|----------|-------|
| Operating System | Ubuntu Linux |
| HDL | Verilog HDL |
| Version Control | Git & GitHub |
| Simulation | Xilinx Vivado|
| RTL Synthesis | Yosys |
| Editor | Visual Studio Code |

---

## Repository Structure

```
apb-digital-peripheral-subsystem
│
├── docs/
├── rtl/
├── tb/
├── reports/
├── scripts/
├── images/
└── README.md
```

---

## Repository Organization

- **docs/** – Project specifications, architecture, register maps and design documentation.
- **rtl/** – Synthesizable Verilog RTL modules.
- **tb/** – Functional verification testbenches.
- **reports/** – RTL synthesis and analysis reports.
- **scripts/** – Automation scripts for simulation and synthesis.
- **images/** – Block diagrams, timing diagrams and simulation waveforms.

---

## Design Philosophy

The objective of this project is to develop a modular and reusable digital peripheral subsystem that reflects industry-standard RTL design practices used in embedded SoC development. The implementation emphasizes clean RTL architecture, modular IP design, functional correctness, synthesizability, and maintainable technical documentation.

---

## Author

**Pushpendra Singh**

B.Tech Electronics and VLSI Engineering

Dr. B. R. Ambedkar National Institute of Technology Jalandhar