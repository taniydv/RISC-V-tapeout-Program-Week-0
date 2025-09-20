# RISC-V-tapeout-Program-Week-0
Welcome to my journey of RISC-V tapeout program!!! 
In this program, we are designing the RISC-V core. Week 0 deals with the basic design flow of an SoC and its planning, which starts from the C-level program compiled using the GCC compiler and specs (C model). Then, this C-level program is converted to the RTL level, which is further divided into the processor and peripherals/IPs. This process is called the SoC design flow. After that, it is converted into SoC integration, and a GDSII file is obtained, which is then sent to the foundry for fabrication.
# Task 1: Installation of open source tools
         i) iverilog
		 ii) GTKWAVE
		 iii) Yosys
###  resizing Ubuntu window 
$ sudo apt update

$ sudo apt install build-essential dkms linux-headers-$(uname -r)

$ cd /media/taniya/VBox_GAs_7.2.0/

<img width="1473" height="854" alt="Screenshot 2025-09-20 141407" src="https://github.com/user-attachments/assets/1a704440-9a12-4093-bb81-6c07cd595ca1" />


### Iverilog installation
$ sudo apt-get update

$ sudo apt install iverilog

<img width="785" height="289" alt="Screenshot 2025-09-20 142556" src="https://github.com/user-attachments/assets/9497deda-57ee-4753-8331-9c4b0a259183" />

### GTKWAVE
$ sudo apt-get update

$ sudo apt install gtkwave

<img width="786" height="127" alt="Screenshot 2025-09-20 142617" src="https://github.com/user-attachments/assets/46ba8bd0-35fd-4625-8908-5d01ef90b3c7" />

### YOSYS
$ sudo apt-get update

$ git clone https://github.com/YosysHQ/yosys.git

$ cd yosys

$ sudo apt install make    

$ sudo apt-get install build-essential clang bison flex\
    libreadline-dev gawk tcl-dev libffi-dev git\
    graphviz xdot pkg-config python3 libboost-system-dev\
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
	
$ make config-gcc

$ git submodule update --init --recursive

$ make 

$ sudo make install

<img width="803" height="225" alt="Screenshot 2025-09-20 153625" src="https://github.com/user-attachments/assets/292cfaf8-bbda-4567-a7ea-ff87473417b8" />

### Acknowledgement
I'm very grateful to the VSD tean for this RISC V Tapeout SOC Program.
