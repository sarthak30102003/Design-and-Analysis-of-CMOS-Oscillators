# CMOS Oscillator Design and Simulation

## 📌 Overview

This project focuses on the **design, simulation, and comparative analysis** of five widely used oscillator topologies using **CMOS technology**. Oscillators are essential components in digital and analog VLSI systems for timing, signal generation, and frequency synthesis. The designs were implemented and simulated using schematic-based tools to evaluate performance across different domains.

## 🧠 Key Topologies Covered

1. **3-Stage CMOS Ring Oscillator**
2. **5-Stage CMOS Ring Oscillator**
3. **Colpitts Oscillator**
4. **Hartley Oscillator**
5. **Wien Bridge Oscillator**

Each oscillator type was studied for:
- Working principle  
- Design methodology  
- Frequency of operation  
- Strengths and limitations  
- Simulation-based validation  

## 🔬 Simulation Results

| Oscillator         | Frequency (Approx.) | Key Features                               |
|-------------------|---------------------|--------------------------------------------|
| 3-Stage Ring       | 2.08 GHz           | High speed, compact, digital integration   |
| 5-Stage Ring       | 1.25 GHz            | Improved stability, more phase outputs     |
| Colpitts           | 159.15 MHz          | Low phase noise, LC tank based             |
| Hartley            | 11.25 MHz           | Tunable frequency, inductive feedback      |
| Wien Bridge        | 9.95 kHz            | Low distortion, ideal for audio range      |

## ⚙️ Tools & Technologies

- **CMOS Inverter-based schematic design**
- **SPICE-based simulation**
- Passive elements (R, L, C) for LC and RC tank circuits
- Focus on analog design principles and layout considerations

## 📈 Comparative Summary

- **Ring Oscillators** are ideal for compact, on-chip integration with trade-offs in phase noise.
- **Colpitts and Hartley Oscillators** offer stable sinusoidal outputs suitable for RF circuits.
- **Wien Bridge Oscillator** provides clean audio-frequency sine waves with minimal distortion.

## 🎯 Learning Outcomes

- Understood oscillator fundamentals across both digital and analog domains.
- Practiced CMOS-based schematic design for both high-speed and low-frequency circuits.
- Performed trade-off analysis for frequency, stability, and integration complexity.
- Strengthened knowledge in choosing oscillator architectures based on application requirements.

## 📚 References

- Behzad Razavi, "The Ring Oscillator," *IEEE Solid-State Circuits Magazine*, 2019.
- Electronics Tutorials – Colpitts Oscillator Design
- Dash Sandeep K. et al., "Optimal Ring Oscillator Design," *Hindawi Journal of Electrical and Computer Engineering*, 2023.
- "Colpitts Oscillator," "Hartley Oscillator," "Wien Bridge Oscillator" – Wikipedia
- US Patent 4891609A – *Ring Oscillator*
