# XAI3 - PDP (Partial Dependence Plots)

This repository contains the solution to **Exercise 5** of the XAI3 practical assignment, focused on model-agnostic interpretability techniques using **Partial Dependence Plots (PDPs)**.

## Contents

| File | Description |
|------|-------------|
| `XAI3.pdf` | Original exercise instructions. |
| `day.csv` | Daily bike rental dataset. |
| `kc_house_data.csv` | Housing prices dataset. |
| `hour.csv` | Hourly bike rental dataset (not used directly). |
| `pdp_bikes.R` | R code for unidimensional and bidimensional PDPs using `day.csv`. *(pending upload)* |
| `pdp_houses.R` | R code for housing price prediction PDPs. *(pending upload)* |
| `XAI3_Report.pdf` | Report including comments, plots, and analysis. *(pending upload)* |

## Exercises Completed

1. **Unidimensional PDPs** for the variables:
   - `days_since_2011`, `temp`, `hum`, `windspeed` in relation to predicting `cnt` (bike rental count).

2. **Bidimensional PDP** using `temp` and `hum` to analyze combined effects.

3. **Housing price prediction PDPs**, using features such as `bedrooms`, `bathrooms`, `sqft_living`, etc.

## Tools Used

- Language: `R` (also compatible with Python)
- Libraries: `randomForest`, `pdp`, `ggplot2`, `dplyr`
- Version control: `Git` and `GitHub`

## Author

**EDM33**  
`edmetsinf33@gmail.com`  
Universitat Politècnica de València (UPV)




