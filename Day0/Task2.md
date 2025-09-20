### **TASK 2 - System requirements & TOOLS INSTALLMENT**

### System Requirements
- **Operating System**: Ubuntu 20.04 or higher
- **Memory (RAM)**: 6 GB minimum
- **Storage**: 50 GB HDD
- **CPU**: 4 vCPU (or equivalent multi-core processor)


### TOOLS Installation Instructions
#### **Yosys**

```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
![Alt text](Images/yosys_installation.png)

#### **Iverilog**
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
![Alt text](Images/iverilog_installation.png)
#### **gtkwave**
```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```
![Alt text](Images/gtkwave_installation.png)

