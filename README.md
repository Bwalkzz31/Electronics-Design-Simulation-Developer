# ⚡ Electronics Design & Simulation Portfolio

Engineered and validated a regulated DC power supply using circuit design principles and SPICE-based simulation. This project focuses on voltage regulation, ripple suppression, and performance under varying load and input conditions.

---

## 📌 Project Overview

Engineered and validated a **5V regulated DC power supply** designed to maintain stable output under varying input voltage and load conditions. The design was analyzed using LTspice, focusing on voltage regulation, ripple suppression, and transient performance.

The system was tested across multiple operating scenarios to evaluate stability, efficiency, and response to dynamic load changes.

---

## 📊 Performance Results

Simulation results confirm that the system maintains stable output across tested conditions:

* Output Voltage: **5V ±1%**
* Output Ripple: **< 50mV peak-to-peak**
* Load Stability: Maintained across **0.1A to 1A**
* Line Regulation: Stable across **7V–12V input range**

Results indicate reliable performance under both steady-state and dynamic conditions.

---

## 📸 Design & Simulation Preview

### 🔌 Circuit Schematic

![Schematic](images/schematic.png)

### 📊 Output Voltage Stability (Transient Response)

![Transient](images/transient.png)

<!-- Uncomment when available
### ⚡ Ripple Measurement (AC Analysis)
![Ripple](images/ripple.png)

### 📉 Load Regulation Test
![Load Regulation](images/load_test.png)
-->

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

The system was designed using a linear voltage regulation topology to prioritize low noise and output stability.

Key considerations included:

* Maintaining consistent voltage output across variable load conditions
* Minimizing ripple through appropriate capacitor selection
* Ensuring stable transient response during load switching events

Simulations were used to validate performance and identify potential instability under edge conditions.

---

## 🧠 Design Decisions

* **Regulator Selection:**
  A linear regulator topology was selected to reduce output noise and simplify circuit design, making it suitable for low-noise applications despite lower efficiency compared to switching alternatives.

* **Capacitor Sizing:**
  Output capacitance was chosen to balance ripple reduction and transient response, preventing voltage dips during sudden load increases.

* **Input Range Handling:**
  The circuit was designed to operate reliably across a 7V–12V input range while maintaining output stability.

* **Stability Considerations:**
  Simulations were used to verify that the system remained stable without oscillation under varying load conditions.

---

## 🧪 Test Scenarios

* Startup response under nominal input voltage
* Load variation from **0.1A to 1A**
* Input voltage fluctuation (**7V–12V range**)
* Ripple measurement under steady-state conditions

---

## ⚠️ Limitations & Considerations

* Efficiency is lower compared to switching regulators due to linear regulation losses
* Heat dissipation may increase at higher load currents
* Design prioritizes stability and low noise over maximum efficiency

Future iterations could incorporate a switching regulator to improve efficiency while maintaining acceptable ripple levels.

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
* Circuit Design & Analysis
* Electrical Debugging Techniques

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
* Integration with microcontroller-based monitoring
* Exploration of switching regulator design for improved efficiency

---

## 👤 Author

**Britany Walker**
IT Management Student | Aspiring IT & Systems Professional

* GitHub: https://github.com/Bwalkzz31
* Portfolio: https://bwalkzz31.github.io

---
