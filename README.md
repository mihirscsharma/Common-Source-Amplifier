# Common-Source-Amplifier: Design, Simulation, and Performance Validation

This project showcases the design, simulation, and performance validation of a Common Source (CS) amplifier with current mirror biasing, implemented in Cadence Virtuoso.

The design was tested across process-voltage-temperature (PVT) corners and verified using Monte Carlo analysis.

## **Key Concepts:**

1. Analog IC Design  
2. Current Mirror Biasing  
3. Small-Signal Gain & Bandwidth Optimization  
4. THD (Linearity) Characterization  
5. PVT Variation Testing  
6. Monte Carlo Yield Simulation  

## **Objective:**

Design a CS amplifier that:  
1. Achieves >14 dB voltage gain  
2. Has >10 GHz bandwidth  
3. Consumes <2.5 mW power  
4. Maintains linearity across varying input amplitudes  
5. Passes all five PVT corners (tt, ff, fs, sf, ss)  
6. Achieves high yield under Monte Carlo simulation  

## **Procedure Summary:**

1. Designed and biased the amplifier using a current mirror topology.  
2. Built the schematic and testbench in Cadence Virtuoso  
3. Ran AC, transient, THD, PVT, and Monte Carlo simulations  

## **Monte Carlo and PVT Testing:**

Simulated across:

1. 5 Process Corners: tt, ff, fs, sf, ss  
2. Voltage: 0.95V, 1.0V, 1.1V  
3. Temperatures: 10°C, 45°C, 75°C  

## **Tools Used:**

1. Cadence Virtuoso  
2. Spectre Simulator (AC, Transient, and Monte Carlo)  
3. Parametric Analysis  
4. DFT/FFT for THD calculation  

## **References:**

- EE 332 Lab 2 Specification Sheet (Spring 2025)  
- Instructor resources from University of Washington Canvas portal  
