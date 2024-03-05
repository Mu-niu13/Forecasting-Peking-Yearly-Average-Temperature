## Peking Yearly Temperature Forecast

### Project Overview
The primary aim of this project is to develop and refine a predictive time series model capable of forecasting annual temperatures in Peking(Beijing), 
utilizing a historical dataset spanning from 1821 to 2012. The goal is to select and optimize a forecasting model that demonstrates high accuracy in 
predicting future temperatures by analyzing past temperature trends and patterns.

### Methodology
The project involved several key steps, including data preprocessing, analysis, model selection, parameter estimation, diagnostic checking, and finally, 
forecasting. A comprehensive approach was taken to ensure the model's accuracy, including:
* Data Preprocessing: Cleaning and preparing the data for analysis, including handling missing values and transforming monthly observations into yearly averages.
* Model Identification: Utilizing ACF and PACF plots to identify potential model parameters.
* Model Selection and Estimation: Selecting the optimal model based on the AICc criterion and estimating model parameters.
* Diagnostic Checking: Assessing the model's performance through various statistical tests to ensure its validity.

### Result
The final model chosen for forecasting Beijing's yearly average temperature was an ARIMA model, which showed satisfactory performance in both fitting 
the historical data and forecasting future temperatures. The project successfully demonstrated the ability to forecast future temperatures with a high degree of accuracy.

### Tools and Resources
* Data Source: Climate Change: Earth Surface Temperature Data from Kaggle.
* Software: The analysis and modeling were performed using RStudio.

### Acknowledgments
Special thanks to Professor Raya Feldman for her support and guidance throughout the project, providing a solid foundation in time series analysis 
and invaluable assistance in addressing detailed problems.
