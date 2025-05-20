# **MIPS Processor Design Comparison – CprE 381 Project Part 3**
Final project for CprE 381 comparing three VHDL‐based MIPS processor architectures—**single-cycle**, **software-scheduled pipeline**, and **hardware-scheduled pipeline**—through benchmarking and performance analysis.



## 📁 **Project Structure**
├── src/ # VHDL source files for all three designs\
├── test/ # VHDL testbenches\
├── benchmarks/ # MIPS assembly benchmark programs\
├── results/ # Performance tables and synthesis reports\
├── Proj3_report.pdf # Final written report and analysis\
└── README.md # Project documentation

## ⚙️ **Processor Designs**
- **Single-Cycle Processor**  
  All instructions execute in one cycle; simple control but higher CPI and longer cycle time.
- **Software-Scheduled Pipeline Processor**  
  Compiler inserts NOPs to avoid hazards; shorter cycle time but more instructions.
- **Hardware-Scheduled Pipeline Processor**  
  Hazards handled in hardware; most complex control but typically best overall performance.

## 📊 **Benchmarks & Evaluation**
Benchmarks run on each design:
- Synthetic benchmark (full instruction set)  
- Grendel (provided test)  
- BubbleSort  
- MergeSort
  
**Tracked metrics:**
- Instruction count (MARS)  
- Total cycles (Modelsim)  
- CPI (cycles per instruction)  
- Minimum cycle time (synthesis)  
- Total execution time

## 📈 **Analysis & Optimizations**
Detailed in the report:
- Comparative performance analysis  
- Software optimizations for pipeline efficiency  
- Hardware optimizations per design  
- Program-type suitability for each architecture  
- Key development challenges and lessons learned

## 🧪 **Demo Expectations**
Each team member will demonstrate:
- Running benchmarks on all three processors  
- Explaining trade-offs and performance results  
- Discussing proposed optimizations

