# Steam Game Data Analysis 📊🎮

This repository contains a data science project exploring trends in game quality on the Steam platform over time. 
The analysis investigates whether the rapid increase in annual game releases has led to a decline in average review scores.

## Contents

- `Steam Game Report.pdf` — Final report outlining the project’s motivation, methodology, analysis, and conclusions.
- `steamfdsStudy.ipynb` — Main Jupyter Notebook used to generate all dataframes, statistical tests, and visualisations included in the final report.
- `notebook.ipynb` — Initial exploratory notebook used for early-stage analysis and understanding of the dataset. Contains a variety of draft visualisations and experiments.
- Graph PDFs:
  - `bar1.pdf` — Number of games release per year by review score category.
  - `doubleLine.pdf` — Average review scores and total releases over time for above and below average game reviews.
  - `heatmap.pdf` — Heatmap of review score distribution over time (log scale).
  - `predictedBar.pdf` — Forecasted number of games above/below average using ARIMA.
  - `regression.pdf` — Linear regression prediction of total game releases.

## Summary

Using a dataset of 140,000+ games scraped from the Steam API and SteamSpy by Newbie Indie Game Dev (October 2024), this project:
- Performs data cleaning and merging using `pandas`.
- Applies regression analysis and hypothesis testing (`R²`, `p-value`) to examine the relationship between release volume and review quality.
- Uses time series forecasting (ARIMA) to predict future trends in game releases and review scores.
- Visualises findings with `matplotlib` and `seaborn`.

## Key Findings

- A statistically significant decline in review scores has occurred as game releases surged post-2013.
- Forecasts suggest that by 2029, over 85% of released games may fall below the historical average review score.

## Tools & Technologies

- Python (Jupyter Notebooks)
- pandas, matplotlib, seaborn, statsmodels (ARIMA)

## License

This project is for academic and non-commercial use. Data is sourced from publicly available APIs.
