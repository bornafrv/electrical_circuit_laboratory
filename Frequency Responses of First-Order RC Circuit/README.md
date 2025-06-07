# 📡 Frequency Response Analysis of First-Order RC Circuits

## 📘 Project Overview
This project explores the **frequency response** of first-order RC circuits. The objective is to analyze how such circuits behave as filters (high-pass and band-pass), determine key characteristics like **cutoff frequency**, and observe the **amplitude and phase shift** across a range of input frequencies.

---

## 🔧 Key Components

### 1️⃣ High-Pass RC Filter
- Constructed using a **resistor and capacitor** in series.
- Input: **Sine wave** from a function generator.
- Output: Voltage measured across the resistor.
- Observations:
  - Output voltage and **phase shift** measured at varying frequencies.
  - Phase difference curve plotted between input and output.
  - **Cutoff frequency (f_c)** determined using:
    ```
    f_c = 1 / (2πRC)
    ```
  - Experimental results compared with theoretical predictions using an oscilloscope.

---

### 2️⃣ Band-Pass Filter
- Created by combining **high-pass** and **low-pass** filters.
- Output amplitude and phase recorded across a frequency sweep.
- **Frequency response analysis** includes:
  - **Lower cutoff frequency (f_L)**
  - **Upper cutoff frequency (f_H)**
  - **Center frequency (f_c = √(f_L × f_H))**
  - **Bandwidth (BW = f_H - f_L)**

---

## 📊 Deliverables

- 📐 Circuit schematics for both filter configurations.
- 📉 Plots of amplitude vs. frequency and phase vs. frequency.
- 🧮 Calculations for:
  - Cutoff frequencies
  - Phase angles
  - Bandwidth
- 📄 Final report summarizing:
  - Filtering behavior of RC circuits
  - Comparison of **experimental** and **theoretical** frequency responses
  - Practical insights on signal filtering

---

## 🎓 Course Info

**Course**: Digital Logic Design Laboratory  
📍 **University of Tehran**  
