# Enhanced Cache Management for RISC/MIPS with Machine Learning (ECE 274)

**Report:** [ECE274_Final_Report.pdf](./ECE274_Final_Report.pdf)  
**Course:** ECE 274 – High-Performance Computer Architecture  
**Title:** Design and Implementation of an Enhanced Cache Management Architecture for RISC/MIPS Systems  
**Authors:** Saachi Jaiswal, Hajira Naim • **Advisor:** Dr. Nan Wang • **Date:** May 2024

## 📖 Overview
We build a modular **RISC/MIPS** system in **Verilog** (processor, ALU, memory, cache) and integrate a
**machine-learning model (Random Forest)** to dynamically choose cache **replacement policy** (LRU/LFU)
and **prefetch addresses**, improving **hit rate** and reducing **AMAT**. Data from **ModelSim** runs is
preprocessed and used to train the ML model; predictions feed the cache controller at runtime.  [oai_citation:2‡HN%26SJ+274+Final+Report.pdf](file-service://file-2JmcBoofnSxLPLjEx7kUCL)

## 📂 Repository Structure
- `ECE274_Final_Report.pdf` — full write-up (architecture, methodology, results)  

## 🛠️ Tools
**HDL/Sim:** Verilog, ModelSim  
**ML:** Python, pandas, scikit-learn, NumPy, Matplotlib, Jupyter
