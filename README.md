# FSM-Based Debouncing and Edge Detection in Verilog

This project implements finite state machine (FSM) modules for debouncing mechanical push buttons and detecting input signal edges. The modules are developed in **Verilog** and structured for simulation and synthesis workflows. The primary goal is to ensure clean and accurate signal transitions for use in digital systems.

---

## 🧠 Project Overview

Mechanical switches generate noisy signals with unintended multiple transitions (bounces). This project addresses that challenge by designing FSM-based logic to filter such noise and reliably detect **rising** and **falling edges**. 

Key design goals include:
- Suppressing false triggers caused by bounce
- Detecting valid edges only after debounce time
- Maintaining signal integrity for counter/trigger-based systems

---

## 💻 Features

- **FSM-Based Debouncing**: Designed a state machine that discards transient fluctuations and confirms stable transitions.
- **Edge Detection Logic**: Developed a pulse-generating module to accurately detect both rising and falling edges.
- **Verilog Design**: Entire logic implemented in synthesizable Verilog for digital circuit integration.
- **Testbench Verification**: Included simulation files to test switch bounce behavior and validate edge detection under noisy input conditions.
- **Modular Structure**: Organized in reusable blocks such as synchronizers, counters, decoders, and multiplexers.

---

