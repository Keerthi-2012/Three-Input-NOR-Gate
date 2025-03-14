# CMOS-Based 3-Input NOR Gate Analysis

This project analyzes the working of CMOS transistors in a 3-input NOR gate, covering the design, functionality, and performance under DC and AC inputs.

## 📄 Project Overview
The 3-input NOR gate is a fundamental digital logic gate that outputs a high signal only when all inputs are low. The gate is implemented using CMOS (Complementary Metal-Oxide-Semiconductor) technology, combining PMOS and NMOS transistors to realize the NOR logic function.

### Key Concepts:
- **Logic Function**: Output = NOT (Input1 OR Input2 OR Input3)
- **PMOS Transistors**: Connected in series to form the pull-up network.
- **NMOS Transistors**: Connected in parallel to form the pull-down network.

## 🏗️ CMOS Gate Design
### Pull-Up Network (PMOS):
- Multiple PMOS transistors are connected in series between the output and the power supply (VDD).
- If all inputs are low, all PMOS transistors turn on, pulling the output to VDD (logic high).

### Pull-Down Network (NMOS):
- Multiple NMOS transistors are connected in parallel between the output and ground (GND).
- If any input is high, the corresponding NMOS transistor turns on, pulling the output to GND (logic low).

## 🧪 Functional Behavior
| Inputs | Output |
|--------|--------|
| 0, 0, 0 | 1 |
| 0, 0, 1 | 0 |
| 0, 1, 0 | 0 |
| 0, 1, 1 | 0 |
| 1, 0, 0 | 0 |
| 1, 0, 1 | 0 |
| 1, 1, 0 | 0 |
| 1, 1, 1 | 0 |

## 📊 Analysis
- **DC Analysis**: Verified output behavior under different DC input combinations.
- **AC Analysis**: Studied frequency response and switching characteristics.

## 🚀 How to Run
1. Open the simulation file in NGSPICE or any compatible SPICE simulator.
2. Run the DC and AC analysis.
3. Observe the output waveform and confirm logic operation.

## ✅ Results
- Verified correct NOR gate behavior.
- Observed expected high/low output levels based on input states.
- Analyzed AC performance for frequency-dependent behavior.

---

