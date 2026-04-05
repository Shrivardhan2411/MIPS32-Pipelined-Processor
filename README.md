# **🖥️ 32-bit MIPS Pipelined Processor in Verilog**



**📌 Overview**



This project presents the design and implementation of a 32-bit MIPS-like processor using Verilog HDL, based on a 5-stage pipelined architecture. The processor demonstrates core concepts of Computer Architecture and RTL Design, including instruction execution, pipelining, and memory operations.



#### **⚙️ Key Features**

* 🧠 32-bit MIPS-like processor design
* 🔄 5-stage pipeline architecture:

&#x09;1. Instruction Fetch (IF)

&#x09;2. Instruction Decode (ID)

&#x09;3. Execute (EX)

&#x09;4. Memory Access (MEM)

&#x09;5. Write Back (WB)

* 🧩 Modular RTL design (ALU, Register File, Control Unit, Memory, PC)
* 🔀 Supports:

&#x09;1. R-type instructions (ADD, SUB, AND, OR, SLT, MUL)

&#x09;2. I-type instructions (ADDI, SUBI, SLTI, LW, SW)

&#x09;3. Branch instructions (BEQZ, BNEQZ)

* ⏱️ Dual-phase clocking (clk1 \& clk2) for pipeline stage separation
* 🧪 Functional verification using testbenches and waveform analysis



#### **🧪 Testbenches**

🔹 Testbench 1: Basic Arithmetic

&#x09;-Performs ADD and ADDI operations

&#x09;-Verifies register write-back functionality

🔹 Testbench 2: Memory Operations

&#x09;-Demonstrates load and store instructions

&#x09;-Validates memory access behavior

🔹 Testbench 3: Loop Execution (Factorial)

&#x09;-Implements a loop using branch instructions

&#x09;-Computes factorial of a number stored in memory

&#x09;-Demonstrates:

&#x09;	-Branching

&#x09;	-Iterative execution

&#x09;	-Data dependency handling (using dummy instructions)





#### **🛠️ Tools \& Technologies**

* Verilog HDL
* RTL Design
* Computer Architecture
* GTKWave (waveform visualization)
* ModelSim / Cadence (simulation)





#### **📂 Project Structure**



MIPS32-Pipelined-Processor/

│── src/

│   └── pipe\_MIPS32.v

│

│── testbench/

│   ├── test\_eg1.v

│   ├── test\_eg2.v

│   ├── test\_eg3.v

│

│── results/

│   └── (waveform files .vcd)

│

│── README.md

│── .gitignore





#### **📊 Sample Output**



Example (Factorial Program):



Input  : 4

Output : 24





#### **🎯 Learning Outcomes**

* Understanding of pipelined processor design
* RTL-level hardware design using Verilog
* Instruction execution and datapath design
* Pipeline hazards and their impact
* Simulation and waveform debugging



#### **👨‍💻 Author**



##### **Shrivardhan Baviskar**

##### **B.Tech Electronics \& Telecommunication Engineering**

##### **Vishwakarma Institute of Technology, Pune**



##### **🔗 GitHub Repository**



**👉 https://github.com/Shrivardhan2411/MIPS32-Pipelined-Processor**

