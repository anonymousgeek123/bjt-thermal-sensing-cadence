# bjt-thermal-sensing-cadence
# BJT-Based Thermal Biasing System

Analog temperature sensing circuit designed and simulated in Cadence Virtuoso 
as part of BEVD204L Electronic Circuits, VIT Chennai (Winter 2025-26).

## Overview

Implements a BJT-based PTAT (Proportional-To-Absolute-Temperature) sensing 
circuit with adaptive biasing to achieve stable thermal monitoring across a 
wide temperature range (-20°C to 125°C).

## Circuits Designed

| Circuit | Description |
|--------|-------------|
| Circuit 1 | Basic BJT PTAT sensor — generates IPTAT output |
| Circuit 2 | Improved design with CTAT + PTAT, outputs stable VREF |
| Adaptive Biasing | Dynamically adjusts bias current to compensate thermal drift |
| Class A Amplifier | Applied to Circuit 2 for signal amplification and stability |

## Key Results

- Circuit 2 achieves a significantly more linear PTAT slope vs Circuit 1
- Adaptive biasing flattens the voltage-temperature curve from -20°C to ~90°C
- After biasing: reduced output fluctuation and improved thermal stability
- PTAT voltage confirmed proportional to absolute temperature: ΔVBE = (kT/q)ln(n)

## Tools Used

- Cadence Virtuoso (Schematic & Simulation)
- DC, Transient, and Temperature sweep analyses

## Team

Sonakshi Agrawal, Sanjana Chejeti, K. Shrihita  
VIT Chennai — April 2026

## Report

Full analysis, methodology, and results in `report.pdf`
