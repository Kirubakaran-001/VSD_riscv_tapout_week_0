# VSD_riscv_tapout_week_0

## 📝 Overview :
This repository contains code, and documentation for the RISC-V Reference SoC Tapeout Program. The project walks through the complete process: from RTL design, simulation, and verification, to physical implementation and tapeout using Synopsys EDA tools and the SCL180 PDK.

## 👉 Week 0 :
For week 0 aim is to install a virtual box and install the tool. 

## 📜 Acknowledgment :
### Program Leadership & Support :
   I am thankful to Kunal Ghosh and Team VLSI System Design (VSD) for the opportunity to participate in the ongoing RISC-V SoC Tapeout Program.
             
## ✨ Getting Started :

1. 📂 Install your prefered IOS (Ubuntu 20.00 or above) and install virtual box, create a virtual space with specification of 
    ```
   6 GB RAM,
   50 GB HDD,  
   4vCPU.
    ```
2. 🧪 if you can't access the root the use this commands in the terminal to access the root
Step 1 :
    ```
             su
      ```
![root_access](https://github.com/Kirubakaran-001/VSD_riscv_tapout_week_0/blob/97a182674454687294cf06e039c25dd3e90a848e/root%20access%20command.jpg)
  
  Step 2 :
   ```
             usermod -aG sudo username
   
   ```
  


3.📂 to install yosys use this commands 

   ```
      sudo apt-get update 
      git clone https://github.com/YosysHQ/yosys.git 
      cd yosys 
      sudo apt install make (If make is not installed please install it)  
      sudo apt-get install build-essential clang bison flex \ 
        libreadline-dev gawk tcl-dev libffi-dev git \ 
        graphviz xdot pkg-config python3 libboost-system-dev \ 
        libboost-python-dev libboost-filesystem-dev zlib1g-dev 
      make config-gcc 
      make  
      sudo make install
   ```
### Output image :
  ![yosys]()


4.📂 to install iverilog : 
      ```
      sudo apt-get update 
      sudo apt-get install iverilog
      ```
### Output image :
  ![yosys]()

5. 📂 to install gtkwave : 
    ```
      sudo apt-get update 
      sudo apt-get install gtkwave
      ```
### Output image :
  ![yosys]()




