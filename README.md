# RISC-V SoC Tapeout Journal
RISC-V SoC TapeOut Training by The VSD team!!
<br> 
Welcome to my journey through the VSD-HDP program! This repository serves as a personal journal, documenting my progress, key learnings, and the outcomes of my work throughout the training.

# Day 0: Tools Installation

## :computer: System Requirements

Before starting with the training, the following system requirements were verified and met to ensure a smooth workflow.

- **Virtual Machine:** Oracle Virtual Box
- **Operating System:** Ubuntu 20.04+
- **Hardware Specifications:**
  - RAM: 6GB
  - Storage: 50GB HDD
  - CPU: 4vCPU

## :hammer_and_wrench: Tool Installation Status

The following is a summary of the tools installed. The installation steps were followed as provided by the VSD team and verified to be successful.

### Yosys

**Summary:** Yosys was successfully installed by cloning the official repository, installing all necessary dependencies, and then compiling and installing the tool using `make`.

**Steps Followed:**
1. Updated the package list.
2. Cloned the Yosys repository from GitHub.
3. Installed essential build tools like `make`.
4. Installed all required dependencies using `apt-get`.
5. Configured the build with `make config-gcc`.
6. Compiled the source code with `make`.
7. Installed the final binaries with `sudo make install`.

### Icarus Verilog (Iverilog)

**Summary:** Iverilog was installed successfully using the apt package manager, which made the process straightforward and quick.

**Steps Followed:**
1. Updated the package list.
2. Installed Iverilog directly using `sudo apt-get install iverilog`.

### GTKWave

**Summary:** GTKWave, the waveform viewer, was easily installed via the package manager.

**Steps Followed:**
1. Updated the package list.
2. Installed GTKWave with `sudo apt install gtkwave`.

### OpenSTA

**Summary:** OpenSTA, an additional tool for static timing analysis, was not a requirement for the SFAL participants but the link to the official repository is provided here for reference.

- [OpenROAD Project/OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA)
