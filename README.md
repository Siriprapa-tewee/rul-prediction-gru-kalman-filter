# rul-prediction-gru-kalman-filter
## Remaining Useful Life Prediction of Turbofan Engines Using Machine Learning

**DPST Summer Camp Research Project | April 2026 – Present**

### Overview
This research investigates machine learning approaches for predicting the Remaining Useful Life (RUL) of turbofan engines using the NASA C-MAPSS dataset. The project explores GRU-based models and Kalman Filtering to improve prediction performance and stability, with a focus on predictive maintenance applications.

### Research Objectives
- Develop machine learning models to estimate the remaining useful life of turbofan engines.
- Explore GRU-based models for learning temporal patterns in engine degradation data.
- Investigate Kalman Filtering to improve prediction stability.
- Evaluate model performance across four NASA C-MAPSS subsets.

### Dataset
The study uses the **NASA C-MAPSS turbofan engine degradation dataset**, covering four subsets:
- FD001
- FD002
- FD003
- FD004

### Methodology
- **Data Preprocessing:** Prepare sensor measurements and time-series data for RUL prediction.
- **GRU-Based Modeling:** Explore recurrent neural networks to capture temporal degradation patterns.
- **Kalman Filtering:** Investigate filtering techniques to improve prediction stability.
- **Performance Evaluation:** Evaluate predictions using RMSE and the NASA scoring function across all four subsets.

### Experimental Results

| Dataset | RMSE | NASA Score |
|---|---:|---:|
| FD001 | 12.74 | 280 |
| FD002 | 12.55 | 777 |
| FD003 | 13.61 | 572 |
| FD004 | 15.07 | 1,170 |

These results summarize the reported model performance across the four C-MAPSS subsets. RMSE measures prediction error, while the NASA scoring function evaluates prediction errors with an asymmetric penalty.

### Research Support
- Received **THB 10,000 in research funding** through the DPST Summer Camp program.
- Conducted research under faculty advisors from Chiang Mai University and Thammasat University.

### Research Scope
This project explores machine learning methods for predictive maintenance, with the goal of estimating engine degradation and supporting maintenance planning.

### Note
This repository presents an overview of the research methodology and approved experimental results. Source code, datasets, and additional research details will be shared only when permitted.
