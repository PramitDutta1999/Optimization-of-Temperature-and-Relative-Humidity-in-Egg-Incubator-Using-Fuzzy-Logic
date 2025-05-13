# Optimization of Temperature and Relative Humidity in Egg Incubator Using Fuzzy Logic

This project presents a fuzzy logic-based control system designed to optimize temperature and relative humidity in an automatic egg incubator. The system is modeled using Mamdani fuzzy inference and developed in MATLAB using the Fuzzy Logic Toolbox. This work was published and focuses on simulation only—no hardware deployment was carried out.

## Overview

The incubator model is divided into two key incubation phases:
- **Days 1–17**: Early incubation with stable thermal and humidity ranges.
- **Days 18–21**: Final phase with more sensitive adjustments for hatching.

## Files

- `incubator_1-17_days.fis` – FIS configuration for days 1 to 17.
- `incubator_18-21_days.fis` – FIS configuration for days 18 to 21.

## Requirements
- MATLAB (recommended R2020a or newer)
- Fuzzy Logic Toolbox

## Usage
1. Open MATLAB.
2. Load `.fis` file in the Fuzzy Logic Designer
3. Explore and modify the rule base, input/output membership functions, and simulate the system behavior.

This is a simulation-only academic project and was not physically deployed.

## Publication
This work has been published and is available on IEEE Xplore: [View on IEEE Xplore](https://ieeexplore.ieee.org/document/9331155)

