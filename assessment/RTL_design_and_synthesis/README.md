# RTL Design & Logic Synthesis — SKY130A PDK

This directory contains lab screenshots and verification outputs for **RTL Design, Functional Simulation, and Logic Synthesis** completed as part of the **Women in Semiconductors: VLSI Design Engineer Program (570 Hours)** conducted by **VSD – SFAL – ESSCI – Marvell**.

## Module Scope & Workflow
1. **Day 1 — Verilog RTL Design & Functional Simulation:**
   * Wrote synthesizable Verilog RTL modules and testbenches.
   * Compiled and simulated designs using **Icarus Verilog (`iverilog`)** and inspected timing/logic waveforms in **GTKWave**.
2. **Day 2 — Logic Synthesis & Gate-Level Netlist Verification:**
   * Synthesized Verilog RTL into gate-level netlists mapped to the SkyWater 130 nm standard-cell library (`sky130_fd_sc_hd`) using **Yosys**.
   * Analyzed cell statistics, area/gate usage, and synthesized logic schematics (`show`), followed by Gate-Level Simulation (GLS) to verify functional equivalence with RTL.


## Tools & PDK Used
* **PDK & Standard-Cell Library:** SkyWater 130 nm (`sky130_fd_sc_hd`)
* **RTL Simulation & Waveforms:** Icarus Verilog (`iverilog`), GTKWave
* **Logic Synthesis:** Yosys, ABC