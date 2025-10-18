# 4×4 SRAM Design Project

This repository contains the complete design of a **4×4 Static Random Access Memory (SRAM)** array built using 6T bitcells.  
The project covers every stage — from transistor-level design and simulation to RTL abstraction and timing verification.

## 🧩 Features
- 6T CMOS bitcell schematic and simulation
- Column decoder and sense amplifier design
- Precharge circuit with and without equalizer
- 4×4 SRAM array integration
- Read/Write operation verification
- SPICE-based timing extraction and constraint generation
- Optional RTL-level implementation for functional verification

## 🛠 Tools Used
- LTspice for circuit design and simulation  
- Vivado for waveforms matching  
- Verilog for RTL abstraction  

## 📊 Results
- Verified read/write operation for all addresses
- Timing constraints derived from SPICE models
- Sense amplifier and precharge circuit validated for stability

## 🚀 Future Scope
- Add wordline driver and control logic
- Implement 8×8 or 16×16 array scaling
- Integrate with memory controller for SoC testbench

---

**Author:** Gaurav  
**Institute:** IIT (BHU), Varanasi  
**Focus:** SRAM Design | VLSI | Digital & Analog Circuits
