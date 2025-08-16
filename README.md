# Coal Bed Methane (CBM) Material Balance Simulator

Author: Mihir Chandra  
Version: 4 (Seidle-aligned implementation)

---

## Overview
This is a Python-based simulator for material balance analysis of coal bed methane (CBM) reservoirs.  
It follows Seidle’s framework and accounts for both adsorbed gas (Langmuir isotherm) and free gas in cleats.  
The model provides a simple way to estimate OGIP, EUR, and water withdrawal, along with plotting production curves.

---

## Features
- Langmuir isotherm for adsorbed gas
- Free gas in cleats using Seidle’s real-gas Bg definition
- Released gas function:  
  F(p) = G_total(Pi) – G_total(p)  
- Forecasted cumulative gas:  
  Gp = f × F(p)
- Compressibility-based water withdrawal estimate
- Heuristic priors for Langmuir parameters if lab data is not available
- Interactive command-line input
- Plot of cumulative gas produced vs. pressure depletion

---
