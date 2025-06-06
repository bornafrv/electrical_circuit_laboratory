# ⚡ Transient Response of First-Order RC Circuits – Digital Logic Design Lab

## 📌 Project Overview
This project studies the **transient response** of **first-order RC circuits** to square wave inputs across a range of frequencies.  
The main focus is on analyzing how the **time constant** (τ = RC) affects the charging and discharging behavior of the capacitor, as well as how the circuit behaves under different **input conditions** including **DC offset** and **op-amp configurations**.

---

## 🔧 Key Components

### 1️⃣ Square Wave Input Response
- Input: square wave signal at varying frequencies
- Observed:
  - 📉 Voltage across **capacitor** (charging/discharging curves)
  - 📈 Voltage across **resistor**
- Theoretical analysis using time constant:
  - τ = R × C
- Relationship between **square wave period** and **τ** analyzed:
  - Fast switching → incomplete charging
  - Slow switching → full charge/discharge

---

### 2️⃣ DC Offset Impact
- Study the effect of applying a **nonzero DC offset** to the square wave
- Simulate and compare:
  - Zero-offset input response
  - Positive-offset input response
- Observed:
  - Shift in waveform baselines
  - Capacitor steady-state voltage changes accordingly

---

### 3️⃣ Frequency Dependence
- Simulate and observe circuit at:
  - 🔹 Low frequency
  - 🔸 Medium frequency
  - 🔺 High frequency
- Concepts studied:
  - Charging/discharging speed
  - Reaching **steady state**
  - Overshoot and delay

---

### 4️⃣ Op-Amp-Based First-Order RC Circuit
- Simulated circuit includes an **operational amplifier**
- Input: square wave with **different duty cycles**
- Studied:
  - Response time and voltage swing
  - Steady state under asymmetric duty cycles
  - Frequency-dependent behavior with op-amp feedback

---

## 📈 Deliverables

- 📷 Oscilloscope and simulation screenshots for:
  - RC response with various frequencies
  - Effects of DC offset
  - Op-amp circuit behavior
- 🧮 Calculations and analysis:
  - Time constants
  - Comparison between measured and theoretical curves
- 📄 Final report documenting all stages, with:
  - Diagrams
  - Observations
  - Conclusion on transient and steady-state behaviors

---

## 🛠 Tools & Equipment

- Function Generator  
- Oscilloscope  
- Variable Resistors  
- Simulation Software (e.g. LTSpice, Multisim, Proteus)  
- Operational Amplifier IC (e.g. LM741)

---

## 🎓 Course Information

**Course**: Digital Logic Design Laboratory  
📍 University of Michigan  
