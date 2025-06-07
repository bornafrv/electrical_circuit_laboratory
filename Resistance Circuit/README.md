# 🔌 Resistive Circuits – Power Transfer, Thevenin & Superposition

## 📌 Project Overview
This project explores the behavior of **resistive electrical circuits** through the application of core theorems in circuit analysis:  
- **Maximum Power Transfer Theorem**  
- **Thevenin’s Theorem**  
- **Superposition Theorem**  

Simulations are used to verify theoretical results, calculate power delivery to variable loads, and analyze voltage/current distribution in multi-source networks.

---

## 🔧 Key Components

### 1️⃣ Maximum Power Transfer Theorem

- Objective: Find the value of load resistor `R_L` for which the **power transferred** from the source to the load is **maximized**
- Steps:
  - Calculate **Thevenin resistance** (`R_th`) and open-circuit voltage
  - Vary `R_L` across simulations
  - Plot:  
    📉 `Power vs. R_L`  
  - Confirm:  
    Maximum power occurs when `R_L = R_th`

---

### 2️⃣ Thevenin Equivalent Circuit

- Thevenin voltage (`V_th`) determined from open-circuit condition
- Thevenin resistance (`R_th`) obtained by turning off independent sources
- Simplify the network to a **single voltage source** and **series resistor**
- Validate:  
  - Measured power at `R_L = R_th` matches theoretical prediction

---

### 3️⃣ Superposition Theorem

- Circuit with **multiple voltage sources**
- Procedure:
  - Analyze current and voltage across elements by turning **one source on at a time**
  - Apply **linear superposition**:  
    `I_total = I1 (V1 active) + I2 (V2 active)`
- Compare results with full-circuit simulation

---

## 📈 Deliverables

- 🖥️ Simulation plots for:
  - Power vs. Load Resistance
  - Open-circuit and short-circuit conditions
  - Superposition-based voltage/current values
- 🧮 Theoretical calculations:
  - Power expressions
  - Thevenin/Norton equivalents
- 📄 Final Report:
  - Circuit diagrams
  - Tables of measured values vs. theoretical predictions
  - Error analysis & discussion

---

## 🛠️ Tools Used

- Simulation: `LTSpice`, `Proteus`, `Multisim`, or similar  
- Analysis: `Python`, `Excel`, or manual calculations  
- Components: Resistors, DC voltage sources

---

## 🎓 Course Information

**Course**: Digital Logic Design Laboratory  
📍 University of Tehran  
