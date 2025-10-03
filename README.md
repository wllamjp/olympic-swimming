# Olympic Swimming Gold Medal Forecasting

## Overview
This project analyzes Olympic swimming results (1912-2020) and tracks the overall progression of the core events in swimming through the century by taking the average of each Olympic year. This project also aims to predict gold medal times for future Olympic games in the same core events.

## Features
- Data Cleaning: Standardizes inconsistent time formats (e.g., "ss.mss", "hh:ss.mssssss", "m:ss.ms", "ss") into a standardized "mm:ss.ms" or "sss.ms" for better calculation
- Trend visualization: Plotting Olympic performance trends over time
- Basic Predictive Modeling: Forecasts future gold medal times for:
    - 100m Freestyle
    - 100m Backstroke
    - 100m Breaststroke
    - 100m Butterfly
    - 200m Individual Medley

Predictive Modeling: Built a linear regression model to forecast future gold medal times

Insights: Observed consistent performance improvement over time. Hikes and dips in time improvement can be contributed to changes in FINA rules at the time that may allow movements/equipment that enhance or hinder performance significantly, such as the implementation of tech suits around the 1990's or the banning of full body tech suits for men in 2010

## Dataset
Olympic Swimming Results (1912-2020) from Kaggle
https://www.kaggle.com/datasets/datasciencedonut/olympic-swimming-1912-to-2020


## Tools & Libraries used:
    - Python
    - Pandas
    - NumPy
    - Matplotlib/Seaborn
    - Scikit-learn
    - Data Cleaning
    - Trend Visualization
    - Regression Analysis
