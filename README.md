# Hyunjun-Kim-VLSI-ASIC-Archives
Archive of school projects that are related to the VLSI and ASIC

## VLSI Design Course
This course covers the fundamental and advanced concepts of high-speed arithmetic logic unit (ALU) structures and Very Large Scale Integration (VLSI) design. It focuses on the analysis, design, and optimization of CMOS logic, memory architectures, and the foundational elements of FPGA technology.

### What I learned
*   **Advanced Arithmetic Logic Design**
    *   Learned how to analyze and implement high-speed arithmetic architectures, including **high-speed adders**, **multipliers**, and **dividers**.
    *   Explored the structural layout of Floating-Point Units (FPUs) and the underlying hardware concepts of GPUs.
*   **VLSI & CMOS Optimization**
    *   Gained experience in analyzing CMOS logic circuits across multiple dimensions, including AC/DC characteristics, power/energy consumption, and leakage current.
    *   Studied advanced design methodologies such as `dynamic`, `domino`, and `ratio-ed logic`.
    *   Utilized **Logical Efforts** to optimize path delays and analyze flip-flop circuits.
*   **Memory & FPGA Architectures**
    *   Developed a solid understanding of high-performance memory array structures.
    *   Studied the internal hardware architectures of FPGAs, learning how programmable logic blocks are configured and routed.

## ASIC Design Course
This course focuses on the comprehensive process of designing, analyzing, and testing complex Application-Specific Integrated Circuits (ASICs) and digital VLSI systems. It covers the entire design flow from high-level Hardware Description Languages (HDLs) and logic synthesis to full-custom physical design and automated placement and routing.

### What I learned
*   **ASIC & Physical Design Flow**
    *   Studied the fundamentals of **ASIC design flows** and integrated digital systems.
    *   Gained hands-on experience in **Physical Design**, spanning from `full-custom` layouts to automated implementations, including **automatic placement, routing, and clock-tree synthesis**.
    *   Learned layout validation techniques, including library characterization, performance estimation, and verification checks like `DRC / LVS / PEX`.
*   **CMOS Logic & Timing Analysis**
    *   Analyzed **static CMOS logic gates** and transistors, focusing heavily on electrical characteristics such as delay, DC response, and power consumption.
    *   Mastered **Static Timing Analysis (STA)** to evaluate and guarantee circuit performance and timing margins.
    *   Explored the design, delay, and power analysis of sequential elements like **Flip-flops**.
*   **Memory, Synthesis & Verification**
    *   Studied the architecture and electrical design of **Static Random-Access Memory (SRAM)** arrays.
    *   Utilized Hardware Description Languages (HDLs) for **logic synthesis** to transform RTL descriptions into gate-level netlists.
    *   Learned chip testing methodologies, design verification, and **formal verification** to ensure hardware reliability.

## Project Overview
| Time | Course | Project Title | Program or Language | Description |
| :--- | :--- | :--- | :--- | :--- |
| Fall2025 | EE 466 | EE466_Lab1_Synthesis_Result | Design Complier (DC) | Synthesized 4-bit, 8-bit, 16-bit, and 32-bit multiplier verilog file using Design Complier. Then analyzed each multiplier's timing constraints. |
| Fall2025 | EE 466 | EE466_Lab1_Synthesis_Results | Innovus | Place and Route 64-bit Brent-Kung Adder (BKA), Han-Carlson Adder (HCA), and Kogge-Stone Adder (KSA) using Innovus. |
| Fall2025 | EE 466 | EE466_10bit_KSA | Verilog | Designed 10-bit Kogge-Stone Adder using verilog. |
| Fall2025 | EE 466 | EE466_27bit_CLA | Verilog | Designed 27-bit carry-lookahead adder (CLA) using verilog. |
| Fall2025 | EE 466 | EE466 Project submition | Hspice | Designed and analyze how three different types of flip-flops (ipDCO, HLFF, semi-dynamic DFF) work, timing constraints, power consumption, and area. |

