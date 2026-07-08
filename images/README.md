# APB-Based Digital Peripheral Subsystem

Design and implementation of a modular digital peripheral subsystem for embedded Systems-on-Chip (SoCs) using synthesizable Verilog HDL.

---

## Overview

Modern embedded Systems-on-Chip (SoCs) integrate multiple reusable digital peripherals to interface with external devices and support embedded processor functionality. Common peripherals include GPIO controllers, programmable timers, PWM generators, and interrupt controllers, which communicate with the processor through standardized on-chip bus protocols.

This project presents the design and implementation of a modular APB-based Digital Peripheral Subsystem using synthesizable Verilog HDL. The project follows an industry-oriented RTL development methodology encompassing architecture definition, RTL design, functional verification, RTL synthesis, and technical documentation.

---

## Motivation

Embedded processors require standardized, scalable, and reusable peripheral interfaces to communicate efficiently with external hardware. The AMBA Advanced Peripheral Bus (APB) provides a simple, low-power interface for integrating memory-mapped peripherals within embedded SoCs.

This project aims to develop a reusable digital peripheral subsystem that demonstrates modular RTL design, standard bus integration, and industry-standard ASIC development practices.

---

## Project Objectives

- Design reusable digital IP blocks using synthesizable Verilog HDL.
- Implement an AMBA APB-compliant peripheral subsystem for embedded SoCs.
- Develop modular and parameterized RTL suitable for IP reuse.
- Develop self-checking Verilog testbenches for functional verification using Xilinx Vivado.
- Perform RTL synthesis using Yosys and analyze synthesis reports.
- Maintain structured project documentation following an industry-oriented RTL development workflow.

---

## Digital IP Blocks

The subsystem integrates the following reusable digital IP blocks:

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
Requirements Analysis
        ↓
Architecture Specification
        ↓
RTL Design (Verilog HDL)
        ↓
Functional Verification
        ↓
RTL Synthesis (Yosys)
        ↓
Technical Documentation
```

---

## Development Environment

| Category | Tool |
|-----------|------|
| Operating System | Ubuntu Linux |
| HDL | Verilog HDL |
| RTL Simulation & Verification | Xilinx Vivado |
| RTL Synthesis | Yosys |
| Version Control | Git & GitHub |
| Code Editor | Visual Studio Code |

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

- **docs/** — Project specifications, architecture documents, register maps, protocol notes, and design documentation.
- **rtl/** — Synthesizable Verilog RTL modules.
- **tb/** — Functional verification testbenches.
- **reports/** — RTL synthesis reports and implementation analysis.
- **scripts/** — Automation scripts for simulation and synthesis.
- **images/** — Block diagrams, timing diagrams, and simulation waveforms.

---

## Design Philosophy

The project is developed following an industry-style RTL design methodology with emphasis on modular architecture, reusable digital IP design, synthesizable RTL, functional correctness, verification-driven development, and maintainable technical documentation.

The objective is to build a reusable embedded peripheral subsystem representative of digital IP integration within modern embedded SoCs.

---

## Author

**Pushpendra Singh**

B.Tech Electronics and VLSI Engineering

Dr. B. R. Ambedkar National Institute of Technology Jalandhar