
# Digital Twin-Driven Intrusion Detection for Industrial SCADA

This repository contains code, sample data, and documentation for the paper:

**Ali Sayghe**  
_"Digital Twin-Driven Intrusion Detection for Industrial SCADA: A Cyber-Physical Case Study"_  
Published in MDPI Sensors, 2025.

## Overview

This project implements a digital twin-driven intrusion detection (DT-ID) framework for industrial SCADA systems, focusing on a simulated water treatment plant case study. The framework integrates high-fidelity process simulation, real-time data synchronization, adversarial attack injection, and hybrid anomaly detection using both physics-based and machine learning methods.

## Contents

- `simulation/` — Python and MATLAB/Simulink scripts for process modeling and twin synchronization
- `data/` — Sample sensor and attack data
- `notebooks/` — Example Jupyter notebooks for analysis
- `models/` — Trained ML models (sample)
- `README.md` — Project overview and usage instructions

## Requirements

- Python 3.10+
- MATLAB/Simulink R2023a
- Required Python packages: `simpy`, `opcua`, `pymodbus`, `influxdb-client`, `scikit-learn`, `tensorflow`, `pandas`, `numpy`, `matplotlib`

Install dependencies (example for Python):
```bash
pip install simpy opcua pymodbus influxdb-client scikit-learn tensorflow pandas numpy matplotlib
