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
📂 piopeline     #All Verilog modules  
📂 test   # Testbench for simulation  
README.md      # Documentation  
```

git clone https://github.com/AnantKamat12/MIPS_32_5stage.git  
cd MIPS_32_5stage  




## Instruction Set Examples
| Instruction | Example          | Description             |  
|-------------|------------------|-------------------------|  
| `ADD`       | `ADD $t1, $t2`   | Adds two registers      |  
| `LW`        | `LW $t1, 0($t2)` | Loads word from memory  |  
| `HLT`       | `HLT`            | Halts execution         |  

