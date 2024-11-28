# Risk and Reliability Analytics Project

## Reliability Analysis of Compressor Drive Systems

### **Introduction**
This repository contains the implementation and analysis for the **Reliability of Compressor Drive Systems (CDS)** at the **Kollsnes Gas Processing Plant**. The project evaluates the reliability of key system components under two scenarios:
1. **Non-repairable components**: Components that must be replaced entirely after failure.
2. **Repairable components**: Components that can be restored to functionality after failure.

The objective is to determine if the current system design meets the operational reliability requirements, and propose improvements where necessary.

---

### **Contents**
- **Code**: Python scripts for reliability modeling, including simulations of time-to-failure (TTF) and repair events.
- **Documentation**: Detailed explanations of methodologies, results, and improvements.
- **Figures**: Visualizations such as histograms, fitted distributions, and failure probabilities.
- **Analysis**:
  - Simulation results for non-repairable and repairable components.
  - Statistical models used (Weibull, Exponential, Log-Normal distributions).

---

### **Key Components**
1. **Variable Speed Drive (VSD)**: Controls motor speed and torque. 
   - Modeled using Weibull distribution.
   - Energy efficiency and process control.
2. **Compressor**: Increases gas pressure. 
   - Modeled with exponential distribution based on supplier-provided failure rates.
3. **Gearbox**: Mechanical system with failure rates derived from external datasets.
4. **Motor**: Degradation modeled with physics-based crack growth.

---

### **How to Use**
1. Clone this repository:
   ```bash
   git clone https://github.com/Jaafare-Elabbar-AMSS/Risk_-_Reliability_Project_JY.git
   cd Risk_-_Reliability_Project_JY

