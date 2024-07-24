
## Project Overview

This project, aims to develop accurate 4-week ahead forecasts for mortality using various statistical methods. The dataset includes weekly mortality rates, temperature, pollutant particle size, and two chemical emissions from Paris, France, between 2010 and 2020.

## Dataset

The dataset contains weekly mortality rates and environmental factors (temperature, pollutant particle size, and chemical emissions chem1 and chem2) from Paris, France, over the period 2010 to 2020.

## Methodology

1. **Data Pre-Processing**: Cleaning and transforming the dataset into time series.
2. **Exploratory Data Analysis (EDA)**: Visual inspection, stationarity tests, and correlation analysis.
3. **Model Building**:
   - **DLM (Dynamic Linear Model)**
   - **ARDL (AutoRegressive Distributed Lag)**
   - **Polyck and Koyck Models**
   - **Exponential Smoothing**
   - **State-Space Models**
4. **Model Evaluation**: Selection based on R squared, AIC, BIC, MASE, and other metrics.
5. **Forecasting**: Generating 4-week ahead forecasts using the best-performing models.

## Results

The project identified the best models for forecasting mortality rates based on various metrics, including R squared, AIC, BIC, and MASE. Detailed results and comparisons of the models are provided in the report.

## Conclusion

The best-performing models were used to generate forecasts for the subsequent four weeks. The analysis highlights the effectiveness of the selected statistical methods in forecasting mortality rates influenced by environmental factors.

## Files in the Repository

- `Forecast_Assignment_3.Rmd`: RMarkdown script containing the code and analysis.
