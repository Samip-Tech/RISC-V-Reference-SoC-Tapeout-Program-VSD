# VSD System Design Course - Day 0

## Tools Installation Summary

### System Requirements
- 6GB RAM
- 50 GB HDD
- Ubuntu 20.04+
- 4vCPU

### Tools Installed

1. **Oracle Virtual Machine**
   - Download from: https://www.virtualbox.org/wiki/Downloads

2. **Yosys** - Hardware description language synthesis tool
   ```bash
   sudo apt-get update
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


