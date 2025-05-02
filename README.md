# Mauna Loa CO₂ Forecasting

This project performs time series analysis and forecasting of atmospheric carbon dioxide (CO₂) 
concentrations at Mauna Loa Observatory using ARIMA models.

## Project Description

- Data: Mauna Loa CO₂ measurements.
- Analysis: Seasonal decomposition, stationarity tests, ACF/PACF plots.
- Modeling: ARIMA model selection based on diagnostics.
- Forecast: Future CO₂ levels with uncertainty intervals.

The full workflow is documented in the provided R Markdown (`.Rmd`) file.

## Files

- `research_paper.pdf` — Full research paper explaining methodology and results
- `mauna_loa_forecasting.Rmd` — Main analysis and modeling code.

## How to Use

1. Download or clone the repository.
2. Open `mauna_loa_forecasting.Rmd` in RStudio or another R environment.
3. Run the cells sequentially to reproduce the analysis and figures.

## Requirements

- R (version 4.0+ recommended)
- R packages:
  - `forecast`
  - `tseries`
  - `ggplot2`
  - `fpp2` (optional for extra functions)

You can install packages in R with:

```r
install.packages(c("forecast", "tseries", "ggplot2"))
