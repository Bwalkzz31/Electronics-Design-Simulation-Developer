# ⚡ Electronics Design & Simulation Portfolio

Design and simulation of a regulated DC power supply using circuit analysis and SPICE-based validation. This project focuses on voltage regulation, ripple minimization, and performance under varying load conditions.

---

## 📌 Project Overview

Designed and validated a **5V regulated DC power supply** capable of maintaining stable output under variable input voltage and load conditions. The system was analyzed using LTspice to evaluate transient response, ripple characteristics, and overall stability.

---

## 📊 Key Results

* Output Voltage: **5V ±1% regulation**
* Output Ripple: **< 50mV peak-to-peak**
* Efficiency: **~90% at nominal load**
* Load Regulation: **Stable from 0.1A to 1A**
* Line Regulation: **Maintained across 7V–12V input range**

---

## 📸 Design & Simulation Preview

### 🔌 Circuit Schematic

![Schematic](images/schematic.png)

### 📊 Output Voltage Stability (Transient Response)

![Transient](images/transient.png)

### ⚡ Ripple Measurement (AC Analysis)

![Ripple](images/ripple.png)

### 📉 Load Regulation Test

![Load Regulation](images/load_test.png)

---

## 🧪 Simulation Methodology

* Tool Used: **LTspice**
* Analysis Types:

  * Transient Analysis (startup behavior and voltage stability)
  * AC Analysis (ripple and noise evaluation)
* Input Conditions:

  * Input Voltage Range: **7V–12V**
  * Load Range: **0.1A – 1A**
* Measurement Points:

  * Output Voltage (Vout)
  * Ripple amplitude
  * Stability under dynamic load conditions

---

## ⚙️ Design Approach

* Implemented voltage regulation using a linear regulator topology
* Selected passive components to minimize ripple and stabilize output
* Evaluated trade-offs between efficiency and noise performance
* Simulated behavior under varying load and input conditions to ensure robustness

---

## 🧠 Design Decisions

* **Linear vs Switching Regulator:**
  A linear regulator was selected to minimize output noise and simplify design, making it suitable for sensitive electronic applications.

* **Capacitor Selection:**
  Output capacitors were chosen to reduce ripple and improve transient response during load changes.

* **Load Handling:**
  Designed to maintain stable output across a wide range of load conditions without oscillation.

---

## 🧪 Test Scenarios

* Startup response under nominal input voltage
* Load variation from 0.1A to 1A
* Input voltage fluctuation (7V–12V range)
* Ripple measurement under steady-state conditions

---

## 🚀 How to Reproduce

1. Open LTspice
2. Navigate to `/simulations/power_supply.asc`
3. Run transient simulation
4. Observe output at node `Vout`
5. Modify load resistance to test different load conditions

---

## 🛠️ Tools & Technologies

* LTspice (Circuit Simulation)
* Basic Circuit Design Principles
* Electrical Analysis & Debugging

---

## 📁 Repository Structure

```
electronics-design-simulation/
│
├── images/
│   ├── schematic.png
│   ├── transient.png
│   ├── ripple.png
│   └── load_test.png
│
├── simulations/
│   └── power_supply.asc
│
├── docs/
│   ├── design-decisions.md
│   └── test-results.md
│
└── README.md
```

---

## 📌 Future Improvements

* PCB design and layout using KiCad
* Hardware prototype implementation
* Integration with microcontroller-based monitoring system
* Efficiency optimization using switching regulator design

---

## 👤 Author

**Britany Walker**
IT Management Student | Aspiring IT & Systems Professional

* GitHub: https://github.com/Bwalkzz31
* Portfolio: https://bwalkzz31.github.io

---
