# 16-Bit-RISC-Processor-using-verilog

## 📌 Overview
This project presents the design and implementation of a **16-bit RISC (Reduced Instruction Set Computing) Processor** using **Verilog HDL**.  
RISC processors use a small, optimized instruction set, enabling fast execution and simplified hardware design.  

The processor is modular, consisting of:
- **Arithmetic Logic Unit (ALU)**
- **Register File**
- **Control Unit**
- **Instruction & Data Memory**
- **Program Counter**
- **Testbenches for simulation**

The design is verified through simulation using tools such as **ModelSim** or **Vivado**.

---

## ✨ Features
- 16-bit word length design.  
- Supports **basic arithmetic, logic, memory, and control operations**.  
- Modular structure for easy debugging and extension.  
- **Instruction decoder** for handling RISC-style instructions.  
- Fully verified using **Verilog testbenches**.  

---


---

## 🛠️ Methodology
1. **Processor Architecture**
   - Based on **RISC principles** with a small instruction set.  
   - Instructions execute in a single cycle for efficiency.  

2. **Verilog Implementation**
   - Each module designed in Verilog (ALU, Control, Register File, Memory).  
   - Synchronous design with clock and reset handling.  

3. **Simulation & Verification**
   - Unit tests for individual components.  
   - Integrated system testing with sample instructions.  

---

## 📊 Results
- The processor successfully executes test programs involving arithmetic, logic, branching, and memory access.  
- Waveform simulations confirm correct operation of the pipeline and state transitions.  
- Demonstrates **simplicity, efficiency, and clarity of RISC design philosophy**.  

---

## 💡 Applications
- Educational tool for learning **RISC architecture**.  
- Base design for more advanced processors (e.g., pipelined CPUs).  
- Useful in **FPGA/ASIC-based digital system design**.  

---

## 🚀 Future Enhancements
- Add **pipeline stages** for parallel instruction execution.  
- Support **interrupts and exceptions**.  
- Implement **I/O modules** for hardware interfacing.  
- Expand instruction set for more complex operations.  

---

## 👩‍💻 Authors 
- **Pavan C K**  
Department of Electronics and Telecommunication  
Dr. Ambedkar Institute of Technology, Bengaluru, India  

---

