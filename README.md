# Distribution Analysis Script

## Overview

This script investigates the distribution of financial data, exploring possible deviations from the normal distribution assumption. It is designed to provide insights into the statistical properties of return data for informed financial analysis.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributors](#contributors)
7. [License](#license)

## 1. Introduction

As an essential aspect of financial analysis, understanding the distribution of data is crucial for risk management, investment strategy, and decision-making. This script facilitates the exploration of distribution characteristics, including normality tests, Q-Q plots, and skewness/kurtosis analysis.

## 2. Features

- **Normality Tests:** Perform prominent normality tests (Shapiro-Wilk, Anderson-Darling, Kolmogorov-Smirnov) on stock returns data.
- **Q-Q Plots:** Generate Quantile-Quantile plots to visually assess the normality of the data distribution.
- **Skewness and Kurtosis Analysis:** Evaluate skewness and kurtosis, providing insights into the symmetry and tail characteristics of the distribution.

## 3. Requirements

- Python 3
- Required Python packages: pandas, numpy, yfinance, matplotlib, seaborn, statsmodels, scipy

## 4. Installation

Clone the repository and install the required dependencies:

```bash
git clone [repository_url]
cd distribution-analysis-script
pip install -r requirements.txt
```

## 5. Usage

1. Install the required libraries:

    ```bash
    pip install pandas yfinance matplotlib
    ```

2. Run the script:

    ```bash
    python distribution_analysis_script.py
    ```

3. Use the configure function to input asset tickers and date ranges, as well as hypothesis test parameter values.

4. View the generated distribution plots.

  
## 6. Contributors

[Nicky Taylor](https://github.com/CoderNicky)

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the functionality and usability of the script.

## 7. License

This script is licensed under the [MIT License](LICENSE)
