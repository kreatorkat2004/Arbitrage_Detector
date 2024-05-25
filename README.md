# ArbitrageDetector

This project is a comprehensive analysis of arbitrage opportunities in sports betting, specifically focused on historical data from various seasons. Using datasets sourced from Kaggle, the project aims to identify and analyze potential arbitrage opportunities by examining betting odds for home wins, draws, and away wins.

## Contributors

Andrew Sun,
Jack Guan

## Project Overview

Key features of this project include:

- **Data Collection:** Importing and processing datasets from multiple seasons to extract relevant betting odds.
- **Data Cleaning:** Subsetting and cleaning the data to focus on critical columns and handle missing values.
- **Arbitrage Detection:** Implementing functions to detect arbitrage opportunities by comparing probabilities derived from betting odds.
- **Probability Normalization:** Calculating normalized probabilities for different outcomes to better understand the betting landscape.
- **Optimization:** Using linear programming to maximize returns based on identified arbitrage opportunities.

This project serves as a practical application of statistical analysis and optimization techniques, providing insights into the potential profitability of arbitrage betting strategies.

## Dataset

The datasets used in this project are historical sports betting data sourced from Kaggle. The primary dataset is `final_dataset_with_odds.csv`, along with individual season files from `2000-2001.csv` to `2020-2021.csv`.

## Installation

To use this project, you need to have R and the following R packages installed:

```R
install.packages(c("knitr", "kableExtra", "lpSolve"))
