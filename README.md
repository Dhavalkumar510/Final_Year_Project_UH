
# Predicting Future Stock Trends: An Analytical Approach Using Lloyds Banking Group Data 

Stock market forecasting supports informed decision-making by predicting price movements influenced by macroeconomic trends, investor sentiment, and geopolitical events. This project analyzes Lloyds Banking Group PLC's stock prices using LSTM and ARIMA models with historical data from 2010 to present. The goal is to assess their effectiveness in real-world financial forecasting.
## Acknowledgements

I would like to express my gratitude to my supervisor for their invaluable guidance and support throughout this project. Their expertise and insights have been instrumental in shaping this research.

A heartfelt thanks to the academic community and researchers whose work provided the foundation and inspiration for this study. Special mention goes to the developers of the yfinance library, Prophet, and other tools utilized in this project, as well as the open-source community for making such incredible resources accessible.

Lastly, I appreciate the encouragement and support of my peers, friends, and family, whose unwavering belief in me has been a source of motivation throughout this journey.


## Appendix
In the context of this project, the appendix includes supplementary materials and resources that support the main work, offering additional transparency and reproducibility. The following materials are provided:

Raw Data Files: Historical stock price data for Lloyds Banking Group PLC (2010–2024) used for analysis and model training.

Supplementary Code: Python scripts and Jupyter notebooks for data preprocessing, feature engineering, and experimental configurations not detailed in the main workflow.

Additional Visualizations: Extended plots and figures demonstrating model performance and data trends beyond the primary results.

Evaluation Metrics: Detailed calculations for R², MSE, RMSE, and MAE for all tested models (LSTM, ARIMA, Prophet, and Holt-Winters).

Reference Material: Links to literature, research papers, and online resources referenced in the project.

Documentation: Installation instructions, software dependencies, and usage guidelines for reproducing the experiments.

## Scrrenshots of Model building, Model testing and Prediction
![image](https://github.com/user-attachments/assets/fab06228-b4ce-4c33-aa1c-aaa0b2c96468)
![image](https://github.com/user-attachments/assets/98d4f3fe-046c-41e5-86ee-63e37f76986a)
![image](https://github.com/user-attachments/assets/cb90fdcd-56af-4516-9880-f52dad3b83a4)

## Authors
Dhavalkumar Pithadiya

https://github.com/Dhavalkumar510/Final_Year_Project_UH

## Models 
LSTM: Long Short-Term Memory

SARIMA: Seasonal Auto-Regressive Integrated Moving Average

Prophet: Additive Model for Forecasting Time Series (developed by Facebook)

Holt-Winters: Holt-Winters Exponential Smoothing
## Optimizations

This project optimized forecasting accuracy through hyperparameter tuning (LSTM units, dropout rates, activation functions), advanced preprocessing (data cleaning, scaling), and incorporating domain-specific insights like seasonality and holiday effects. Models were evaluated using metrics (R², MSE, RMSE), and a comparative analysis identified the best-performing approach for stock price prediction.

## Installation

Install with essential library e.g.,
pmdarima, yfinance, fbprophet etc
   
## Supervision

This Project is Supervised by Hasan-Al-Madfai
