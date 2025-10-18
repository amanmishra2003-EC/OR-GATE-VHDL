# ⚙️ OR Gate in VHDL (ModelSim Simulation)

## 📘 Overview
This project implements a basic **2-input OR Gate** using **VHDL** and simulates it in **ModelSim**.  
An OR Gate performs logical addition — the output is **HIGH (1)** if **any one** or **both** inputs are HIGH.

---

## 🎯 Objective
To design and verify the functionality of a **2-input OR Gate** using VHDL and validate its truth table through simulation in ModelSim.

---

## 🧠 Theory
An **OR Gate** is a fundamental digital logic gate that operates as follows:  
- **Y = A + B**  
(where “+” denotes the logical OR operation)

| A | B | Y (A OR B) |
|:-:|:-:|:-----------:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

---

## 🧰 Software and Language
- **Software:** ModelSim — for simulation and waveform analysis  
- **Language:** VHDL (IEEE STD_LOGIC_1164) — for design and testing  

---

## 📊 Simulation Result
✅ The simulated waveform confirms correct OR Gate operation:  
- Output **Y = 1** whenever **A** or **B** is **1**.  
