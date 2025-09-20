# RISC-V_Chip_Tapeout_Program_2025-VSD
Documenting RISC‑V Reference SoC Tapeout Program-VSD

---

## Week 0

<details>
<summary> Task 1: Getting started with Digital VLSI SOC Design and Planning </summary>

### ASIC / SoC Design Flow

1️. Specification – Define functionality, performance, power, area.
2️. RTL Design – Write Verilog/VHDL, modular & synthesizable code.
3️. Verification – Simulate with testbenches, ensure correct behavior.
4️. Synthesis – Convert RTL → gate-level netlist with constraints.
5️. STA – Check timing paths (setup/hold) meet requirements.
6️. DFT – Insert scan chains, generate test patterns.
7️. Physical Design – Floorplan, place, route, CTS, DRC/LVS checks.
8️. Signoff – Final timing, power, physical verification.
9️. Tapeout – Generate GDSII & send to foundry.
10.Silicon Testing – Validate first silicon, apply ECOs if needed.

<details>
<summary> Task 1: Tools Installation </summary>

### Tools for Installation:

1.Oracle VirtualBox (6GB RAM, 50 GB HDD; Ubuntu 20.04+; 4vCPU)
![Oracle VirtualBox](https://i.postimg.cc/MHhPZC1T/Screenshot-2025-09-20-134309.png)
2.Yosys
![Yosys](https://i.postimg.cc/5NGHw06H/Screenshot-2025-09-20-155836.png)
3.Iverilog
![Iverilog](https://i.postimg.cc/nhBLBGy5/Screenshot-2025-09-20-160052.png)
4.gtkwave
![Iverilog](https://i.postimg.cc/1t2tD73k/Screenshot-2025-09-20-160348.png)
