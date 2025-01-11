Here’s a **shorter version** of the README for your GitHub repository:  

---

# Pipelined MIPS32 Processor Simulation 🚀  

A Verilog-based **5-stage pipelined MIPS32 processor** simulating MIPS instructions with hazard mitigation.  

## Features  
- **Pipeline Stages**: IF, ID, EX, MEM, WB  
- Supports **ADD, SUB, LW, SW, BEQ, HLT**, and more.  
- Data & control hazard handling (forwarding, pipeline flushing).  
- **Testbench** for verification.  

## Project Structure  
```
📂 src         # Verilog modules  
📂 testbench   # Testbench for simulation  
README.md      # Documentation  
```  

## Getting Started  
1. Clone the repo:  
   ```bash  
   git clone https://github.com/AnantKamat12/Pipelined-MIPS32.git  
   cd Pipelined-MIPS32  
   ```  
2. Run `mips32_tb.v` in a Verilog simulator (ModelSim, Vivado, etc.).  

## Instruction Set  
| Instruction | Example          | Description             |  
|-------------|------------------|-------------------------|  
| `ADD`       | `ADD $t1, $t2`   | Adds two registers      |  
| `LW`        | `LW $t1, 0($t2)` | Loads word from memory  |  
| `HLT`       | `HLT`            | Halts execution         |  

