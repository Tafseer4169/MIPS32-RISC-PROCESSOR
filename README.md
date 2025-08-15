# MIPS 32-bit Processor (2-Phase Clock, 5-Stage Pipeline)

This project implements a 32-bit MIPS processor in Verilog HDL with a **five-stage pipeline**:
1. Instruction Fetch (IF)
2. Instruction Decode (ID)
3. Execution (EX)
4. Memory Access (MEM)
5. Write Back (WB)

It supports basic **R-type, I-type, and HALT** instructions, two-phase clock operation (`clk1`, `clk2`), and a simple in-memory program.

---

## 📂 Project Structure
├── MIPS_32.v   # MIPS32 processor implementation <br>
├── tb.v        # Testbench <br>
└── README.md   # Project documentation
