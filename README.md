# Pump Outlet Temperature using DWSIM

## Problem Statement
Water at 120 °C and 3 bar is fed into a pump operating at 10% efficiency.
The flow rate of water is 100 kgmole/h and the outlet pressure is 84 bar.
Using the Peng–Robinson equation of state, the outlet temperature of water
is to be determined.

## Simulation Tool
- Software: DWSIM
- Property Package: Peng–Robinson EOS

## Simulation Setup
- Feed temperature: 120 °C
- Feed pressure: 3 bar
- Outlet pressure: 84 bar
- Pump efficiency: 10%
- Molar flow rate: 100 kgmol/h
- Working fluid: Water

## Methodology
1. Water stream was defined with given temperature, pressure, and flow rate.
2. Peng–Robinson was selected as the fluid package.
3. A pump unit operation was added.
4. Pump outlet pressure and efficiency were specified.
5. Simulation was run to determine outlet conditions.

## Results
- Outlet pressure: 84 bar
- Outlet temperature: **137.157 °C** (from simulation)

## Key Learning
- Effect of pump inefficiency on temperature rise
- Use of non-ideal EOS for liquid water at high pressure
- Practical application of energy balance in pumps

## Files Included
- `Water_Pump_Problem.dwxmz`: DWSIM simulation file
![Simulation Results](results.png)
