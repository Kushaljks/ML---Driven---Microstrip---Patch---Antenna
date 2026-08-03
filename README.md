# ML---Driven---Microstrip---Patch---Antenna

This project presents the design, optimization, fabrication, and experimental validation of a 2.45 GHz inset-fed microstrip patch antenna. The objective was to reduce the computational cost of conventional antenna optimization by integrating Machine Learning with electromagnetic simulation.

A comprehensive dataset was generated using ANSYS HFSS through parametric simulations of various antenna geometries. A Random Forest surrogate model was then developed to accurately predict the antenna's return loss (S11), while a Genetic Algorithm was employed to identify optimal design parameters for the target operating frequency.

This project demonstrates the complete antenna development workflow—from electromagnetic simulation and dataset generation to machine learning-assisted optimization, fabrication, and real-world RF measurements.

## Project Workflow

1. Designed the antenna in ANSYS HFSS.
2. Generated the simulation dataset.
3. Trained the ML surrogate model.
4. Optimized antenna dimensions using a Genetic Algorithm.
5. Fabricated the optimized antenna.
6. Measured S11 using a Vector Network Analyzer (VNA).
7. Compared measured results with HFSS simulations.

## My Contributions

- Designed and simulated the microstrip patch antenna using ANSYS HFSS.
- Generated the complete HFSS simulation dataset through parametric sweeps.
- Fabricated the optimized antenna prototype.
- Soldered the SMA connector for RF measurements.
- Performed S11 measurements using a Keysight FieldFox Microwave Analyzer.
- Compared simulated and measured results for validation.
- Contributed to project documentation and presentation.




