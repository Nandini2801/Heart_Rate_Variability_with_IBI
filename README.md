# Heart_Rate_Variability_with_IBI
This repository contains **open-source data**, **code**, and **results** for analyzing Heart Rate Variability (HRV) using Inter-Beat Interval (IBI) data. It includes training data, machine learning models, and scripts for HRV parameter extraction and prediction. Due to copyright restrictions imposed by Omnyk India Pvt Ltd, the complete code cannot be uploaded.

## Folder Descriptions

### 1. **Codes**  
Contains Jupyter notebooks for HRV analysis and model training:  
- **HRV_Analysis.ipynb**: Calculates HRV parameters from raw IBI data.  
- **Stress_Analysis_Model(SVM).ipynb**: Code for training the machine learning model (SVM).
- **Stress_Analysis_Model(XGBoost).ipynb**: Code for training the machine learning model (XGBoost).  
- **Stress_Analysis_Prediction.ipynb**: Generates predictions from raw Omnyk IBI data.  
- **Tabulation_hrvParams.ipynb**: Tabulates HRV parameters, including metrics like SDANN and SDNNI from raw IBI data.
- **Hrv_plotting.ipynb**: Plots HRV parameters for each patients for analysis.
  

### 2. **Saved_Model**  
This folder contains the pre-trained model:  
- **xgb_clf.pkl**: Saved XGBoost classifier model for making predictions.

