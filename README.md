# Common-Source-Amplifier
This project showcases the design, simulation, and performance validation of a Common Source (CS) amplifier with current mirror biasing, implemented in Cadence Virtuoso.

The design was rigorously tested across process-voltage-temperature (PVT) corners and validated for statistical robustness using Monte Carlo analysis.

Key Concepts
Analog IC Design

Current Mirror Biasing

Small-Signal Gain & Bandwidth Optimization

THD (Linearity) Characterization

PVT Variation Testing

Monte Carlo Yield Simulation

📐 Objective
Design a CS amplifier that:

Achieves >14 dB voltage gain

Has >10 GHz bandwidth

Consumes <2.5 mW power

Maintains linearity across varying input amplitudes

Passes all five PVT corners (tt, ff, fs, sf, ss)

Achieves high yield under Monte Carlo simulation

🧪 Procedure Summary
Designed and biased the amplifier using a current mirror topology

Built the schematic and testbench in Cadence Virtuoso

Ran AC, transient, THD, PVT, and Monte Carlo simulations

Verified spec compliance using data from Table 1 constraints

📊 Results Highlights
Metric	Result	Target
Voltage Gain	>14 dB across corners	>14 dB
Bandwidth	>10 GHz	>10 GHz
Power Consumption	<2.5 mW	<2.5 mW
THD (10 mV)	~5.73%	Acceptable
THD (200 mV)	~27.45%	Shows nonlinearity limits
Monte Carlo Yield	✅ All specs passed	High yield

Full frequency and transient responses were recorded for multiple input amplitudes (10–200 mV), confirming linearity limits and amplifier stability.

📈 Monte Carlo and PVT Testing
Simulated across:

5 Process Corners: tt, ff, fs, sf, ss

Voltage: 0.95V, 1.0V, 1.1V

Temperatures: 10°C, 45°C, 75°C

Yield Stats:
High statistical yield across all metrics

Histograms for gain, bandwidth, power, and current confirmed tight variation and reliable design margins

🛠 Tools Used
Cadence Virtuoso

Spectre Simulator (AC, Transient, and Monte Carlo)

Parametric Analysis

DFT/FFT for THD calculation

🧾 Reference
EE 332 Lab 2 Specification Sheet (Spring 2025)

Instructor resources from University of Washington Canvas portal

💡 Takeaways
This lab demonstrated the importance of robust analog design under real-world variability. By combining current mirror biasing with layout-aware design and extensive simulation, the amplifier met stringent spec requirements and showcased strong statistical reliability.
