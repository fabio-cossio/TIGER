# TIGER ASIC

This repository contains:

## Time-walk correction curves

These curves are produced by the circuit simulation and provide different corrections according to:

- threshold settings (0.5-15 fC)
- input signal charge (1-50 fC)
- input signal duration (50-300 ns, step 10ns)


## Calibration files for Efine-charge conversion

Each row lists:

- channel_id
- linear fit constant parameter
- linear fit slope parameter


## Calibration files for TDCs

- ***old calibration***: LUT using TDC scan performed in Turin
- ***new calibration***: LUT using IHEP data from real acquisition

Each row lists:

- channel_id
- Tfine_min_tac0, Tfine_max_tac0
- Efine_min_tac0, Efine_max_tac0
- Tfine_min_tac1, Tfine_max_tac1
- Efine_min_tac1, Efine_max_tac1
- Tfine_min_tac2, Tfine_max_tac2
- Efine_min_tac2, Efine_max_tac2
- Tfine_min_tac3, Tfine_max_tac3
- Efine_min_tac3, Efine_max_tac3 

