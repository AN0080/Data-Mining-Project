# Project Title  
Electric Load Forecasting and Classification Performance Evaluation Based on Multivariate Meteorological Features

**Chenglin Liu**   

---

## Abstract  
This study constructs a predictive model for electric load based on multivariate meteorological features and historical load data using machine learning techniques. Through data preprocessing, feature engineering, model training, and hyperparameter tuning, the final model achieves strong regression performance on the test set. Additionally, load classification evaluation based on predicted results validates the model’s practicality and stability. Future work will explore more complex models and multi-source data fusion to improve prediction accuracy.

---

## Rationale  
With the development of industrialization and smart grids, accurate electric load forecasting is critical for ensuring grid security and optimizing resource allocation. Meteorological factors significantly impact electricity demand, and integrating multivariate weather features can improve prediction accuracy, supporting energy management, emission reduction, and promoting sustainable development.

---

## Research Question  
How can multiple meteorological variables and historical load data be combined through machine learning methods to achieve high-precision electric load forecasting and effective load state classification?

---

## Data Sources  
The data consist of multi-year meteorological monitoring and electric load records from a specific region, including temperature, dew point, humidity, wind speed, irradiance, and corresponding hourly load values. The data are cleaned and missing values handled to construct time series features for model training.

---

## Methodology  
- Data preprocessing: column normalization, datetime index construction, missing value imputation  
- Feature engineering: rolling means and standard deviations, lag features, polynomial temperature features, time discretization  
- Model training: linear regression baseline and random forest regression with grid search hyperparameter tuning  
- Evaluation metrics: RMSE, MAE, R², learning curves, and residual analysis  
- Classification evaluation: binary classification based on load thresholds, confusion matrix, precision, recall, and F1 score calculation  

---

## Results  
The tuned random forest model outperforms linear regression, with significantly reduced RMSE on the test set. Residual analysis indicates good model fit, and feature importance analysis confirms that meteorological and lagged load features are key drivers. Classification tasks show stable accuracy and F1 scores, demonstrating the model’s potential for load anomaly detection.

---

## Next Steps  
Future directions include exploring deep learning models incorporating spatial meteorological data, leveraging richer external variables to enhance prediction performance; refining classification tasks with multi-class load state identification; and integrating real-time data for online prediction and scheduling optimization.

---

## Conclusion  
This study demonstrates the effectiveness of combining multivariate meteorological features with machine learning for electric load forecasting, providing a data-driven solution for smart grid load management. Future work will focus on improving model complexity and real-time capabilities to advance intelligent energy systems.

---

## Bibliography  
- [1] Liu, C., & Wang, J. (2021). Short-term electricity load forecasting using meteorological features and machine learning techniques. *Energy*, 215, 119107.
- [2] Zhang, Y., & Li, X. (2018). Machine learning approaches for electric load forecasting: A review. *Renewable and Sustainable Energy Reviews*, 94, 854-866.
- [3] Li, M., & Zhao, L. (2022). Meteorology-driven electricity load forecasting model based on random forest. *Electric Power Technology*, 46(3), 1054-1062.

---

## Contact and Further Information  
Chenglin Liu  

Email: liuchenglin080@gmail.com

GitHub: https://github.com/AN0080/Data-Mining-Project.git
