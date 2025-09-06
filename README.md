# VLSI Full Adder Optimization & 4-Bit Multiplier Design

_A hackathon project for **BECE303P – VLSI Systems Design** course at VIT Chennai (Winter 2024–25)._

---

## Project Overview
This project focuses on optimizing the performance of fundamental arithmetic circuits in **VLSI** using **Cadence Virtuoso**.  
We explored **six transistor-level implementations of a full adder** and tested each design for **propagation delay** under two conditions:  

1. Without transistor sizing  
2. With optimized transistor sizing  

The most efficient full adder design was then used as the **core building block** to implement a **4-bit binary multiplier** at the transistor level.

---

##  Tools & Technologies
- **EDA Tool:** Cadence Virtuoso (schematic design & simulation)  
- **Environment:** Linux-based setup for running EDA tools  
- **Optimization:** Manual transistor sizing for W/L ratio tuning  

---

##  Results Summary
-  **Circuit 3** achieved the **least maximum delay** after transistor sizing.  
-  Significant performance improvement observed due to optimized sizing.  
-  Optimized full adder was successfully **integrated into a 4-bit multiplier design**.  
-  Power and delay characteristics of each design were **measured, documented, and compared**.  

---

##  Key Takeaways
- Transistor sizing plays a **crucial role** in delay and power optimization.  
- **Simulation-based analysis** is essential for better architectural choices in arithmetic circuit design.  
- An efficient **full adder design** directly impacts the performance of higher-level units like **multipliers**.  
