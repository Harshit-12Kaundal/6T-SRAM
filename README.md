# 6T SRAM Design

## Overview
This repository contains the design, simulation, and analysis of a **6T SRAM (Six-Transistor Static Random-Access Memory)** cell. The project explores the implementation of a standard 6T SRAM cell used in modern VLSI circuits and its performance characteristics.

## Features
- **Custom-designed 6T SRAM cell** with optimized transistor sizing.
- **SPICE simulations** for read/write operations.
- **DC Analysis** for static behavior evaluation.
- **Analysis of power consumption, delay, and stability.**
- **Performance benchmarking** under different process variations.

## Design Methodology
1. **Schematic Design**: Implemented in **Cadence Virtuoso** using CMOS transistors.
2. **Layout Design**: Optimized layout with minimal area and low leakage.
3. **Simulation & Analysis**: Read/write stability, SNM (Static Noise Margin), power-delay tradeoffs, and **DC Analysis**.

## Tools Used
- **Cadence Virtuoso** for schematic and layout design.
- **Cadence Spectre** for circuit simulations.
- **MATLAB/Python** for result visualization.

## Installation & Usage
### Prerequisites
Ensure the following tools are installed:
- **Cadence Virtuoso** for design and simulations.

### Steps to Simulate
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/6T-SRAM.git
   cd 6T-SRAM
   ```
2. Open the schematic in **Cadence Virtuoso** and verify the design.
3. Run simulations using **Cadence Spectre**.
4. Perform **DC Analysis** to evaluate static characteristics.
5. Analyze output waveforms using MATLAB/Python scripts.

## Simulation Results
- **SNM Calculation**: Stability metrics of the SRAM cell.
- **Power vs. Performance** tradeoff analysis.
- **Process Variation Impact**: Effects of fabrication variations on SRAM operation.
- **DC Analysis Results**: Static behavior insights of the SRAM cell.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

