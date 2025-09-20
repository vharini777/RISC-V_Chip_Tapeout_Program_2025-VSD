# RISC-V_Chip_Tapeout_Program_2025-VSD
Documenting RISC‑V Reference SoC Tapeout Program-VSD

---

## Week 0

<details>
<summary> Task 1: Getting started with Digital VLSI SoC Design and Planning </summary>

### ASIC / SoC Design Flow

- Specification – Define functionality, performance, power, area.  
- RTL Design – Write Verilog/VHDL, modular & synthesizable code.  
- Verification – Simulate with testbenches, ensure correct behavior.  
- Synthesis – Convert RTL → gate-level netlist with constraints.  
- STA – Check timing paths (setup/hold) meet requirements.  
- DFT – Insert scan chains, generate test patterns.  
- Physical Design – Floorplan, place, route, CTS, DRC/LVS checks.  
- Signoff – Final timing, power, physical verification.  
- Tapeout – Generate GDSII & send to foundry.  
- Silicon Testing – Validate first silicon, apply ECOs if needed.  

</details>

<details>
<summary> Task 2: Tools Installation </summary>

### Oracle VirtualBox
- Minimum: 6GB RAM, 50GB HDD, Ubuntu 20.04+, 4 vCPU  

### Linux Tool Setup (Yosys, Icarus Verilog, GTKWave)

#### Yosys
```bash
# Update package lists
sudo apt-get update

# Install Yosys
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make
sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make
sudo make install
cd ..

# Install Icarus Verilog
sudo apt-get install iverilog

# Install GTKWave
sudo apt install gtkwave

</details>
