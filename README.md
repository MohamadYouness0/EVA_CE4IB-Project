# Thermal dynamic model of a two-zone flat: bedroom and toilet

Project for the course EVA, Dynamic Models for Building Energy Management (Prof. C. Ghiaus).

**Team:** Mohamad Youness, Marcel Stranz, Parisa Parand

**Run online:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MohamadYouness0/EVA_CE4IB-Project/HEAD?labpath=EVA_report.ipynb)

## Contents

Two-zone thermal network (17 nodes, 29 branches) with two-layer exterior walls, long-wave
radiation between glazing and walls, infiltration and P-controllers. The report covers the
model, the steady state (DAE vs state-space), the step response, the response to the weather
of Wädenswil (P-controller and dead-band controller) and an insulation thickness study.

## Files

- `EVA_report.ipynb`: the report
- `dm4bem.py`: course module by C. Ghiaus
- `CHE_ZH_Wadenswil.066730_TMYx.2011-2025.epw`: weather data (climate.onebuilding.org)
- `floor_plan.png`: floor plan
- `circuit.png`: thermal circuit
- `section_*.png`: sections of the walls and of the glazing (W2, W4)
- `environment.yml`: dependencies
