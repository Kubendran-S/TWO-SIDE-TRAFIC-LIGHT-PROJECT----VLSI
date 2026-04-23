# 🚦 Two-Way Traffic Light Controller (Verilog)

## 📌 Overview
A Verilog-based FSM project that controls traffic between a main road and a side road. The system uses timers and vehicle detection to manage red, yellow, and green signals efficiently and safely.

## 🎯 Features
- Finite State Machine (FSM) design
- Timer-based signal control (TS, TL)
- Main road priority logic
- Vehicle detection input (C)
- Modular design (FSM + Timer + Top Module)

## 🧠 Working Principle
The controller operates in four states:
1. Main Road Green
2. Main Road Yellow
3. Side Road Green
4. Side Road Yellow

Transitions occur based on timer signals (TS, TL) and vehicle presence (C).

## 🏗️ Project Structure
main_top.v  - Top module  
fsm.v       - State machine logic  
timer.v     - Timing control  
tb.v        - Testbench  

## ⚙️ Inputs & Outputs
Inputs:
- Clk (Clock)
- reset (Reset)
- C (Vehicle detection)

Outputs:
- Main Road → MR, MY, MG
- Side Road → SR, SY, SG

## 🧪 Simulation
Simulated using Vivado/ModelSim. The waveform shows correct signal transitions without X or Z values.

## 📊 State Flow
Main Green → Main Yellow → Side Green → Side Yellow → Repeat

## 🔥 Applications
- Smart traffic systems
- FPGA/VLSI learning
- Embedded control systems

## 🚀 Future Improvements
- Sensor-based dynamic timing
- Emergency vehicle priority
- Real-time FPGA implementation

## 👨‍💻 Author
Kubendran S  
EEE Student | VLSI Enthusiast
