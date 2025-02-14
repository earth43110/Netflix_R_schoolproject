# Netflix Stock Price Prediction using Multiple Linear Regression

## Overview
This project demonstrates the application of **R programming** and **statistical analysis** to predict Netflix's stock price using multiple linear regression. The analysis includes data preprocessing, model building, validation, and hypothesis testing.

## Project Components
### 1. **Dataset**
- The dataset (`Netflix_Dataset.pdf`) includes **historical stock performance** and financial metrics such as revenue, liabilities, operating expenses, and subscriber count.
- A separate `prediction_dataset.pdf` contains hypothetical future values used to forecast stock prices.

### 2. **R Code**
- The `R_code.pdf` file contains the script used for:
  - **Data Import**: Reads stock and financial data.
  - **Model Creation**: Builds a multiple linear regression model using stock-related predictors.
  - **Assumption Testing**: Applies statistical tests such as Durbin-Watson, Breusch-Pagan, and White's test to validate model assumptions.
  - **Visualization**: Creates residual plots and normality plots to assess model fit.
  - **Prediction**: Uses new data to generate stock price forecasts.

### 3. **Statistical Analysis & Report**
- The `Netflix_Report.pdf` outlines the **statistical methodology**, including:
  - Description of financial indicators affecting stock price.
  - Model validation through hypothesis testing.
  - Discussion on regression assumptions (linearity, homoscedasticity, independence).
  - Interpretation of model output, including **adjusted R-squared** and **significance tests**.

## Key Learnings
This project showcases proficiency in:
- **Data Wrangling** with R (dplyr, ggplot2).
- **Building and Evaluating Regression Models**.
- **Statistical Testing** to ensure model reliability.
- **Forecasting** based on real-world business metrics.

## How to Use
1. **Load Data**: Prepare a CSV with stock and financial variables.
2. **Run the R Script**: Execute the provided R code to generate regression insights.
3. **Analyze Outputs**: Check the model summary, residual plots, and prediction results.
4. **Experiment**: Modify inputs in `prediction_dataset.pdf` to test different financial scenarios.

## Conclusion
This project serves as an introduction to **financial modeling with R**, helping understand how business metrics influence stock prices. While simplified, the methodology can be adapted for broader financial forecasting applications.

