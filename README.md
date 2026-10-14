# AIDAMS Lab 3: Bottom-up steel emissions with uncertainty

A bottom-up estimate of China's crude-steel CO2 emissions, built from plant-level data for 2020 to 2030 (Part A). Part B then tests how far those numbers can be trusted: a check against official statistics, matched utilisation, a bootstrap, a Monte Carlo simulation and policy scenarios.

## Files

| File | Content |
|---|---|
| `lab3.ipynb` | The completed notebook, with all outputs |
| `Plant-level_data_Global_Iron_and_Steel_Tracker_June_2026_V1.xlsx` | Plant-level data from Global Energy Monitor (CC BY 4.0) |
| `requirements.txt` | Python packages |

## How to run

1. Install Python 3.10 or later. The notebook was tested with Python 3.12, pandas 3.0, numpy 2.4 and matplotlib 3.10.
2. Install the packages: `pip install -r requirements.txt`
3. Keep the workbook in the same folder as the notebook, or set the `GIST_PATH` environment variable to its location.
4. Open `lab3.ipynb` in Jupyter or VS Code and run **Kernel > Restart & Run All**. A full run takes about 20 seconds.

## Note on the data

The lab names the September 2025 V1 workbook, which Global Energy Monitor no longer distributes. We use the June 2026 V1 release of the same plant-level file. It has the same three sheets. Three columns were renamed (`GEM plant ID`, `Country/area`, `Parent (English)`), and the notebook maps them back to the names the lab uses. Figures quoted in the lab text, such as the 57% to 8% drop in Q5, come from the older release, so they differ from ours.

## Sources

- Global Energy Monitor, *Global Iron and Steel Tracker*, June 2026 (V1) release, licensed under CC BY 4.0: <https://globalenergymonitor.org/projects/global-iron-and-steel-tracker/>
- worldsteel, *World Steel in Figures*, 2022 to 2025 editions (China crude steel production, 2020 to 2023): <https://worldsteel.org/data/world-steel-in-figures/>
