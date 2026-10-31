# rul-prediction-gru-kalman-filter
# Remaining Useful Life Prediction of Turbofan Engines Using Machine Learning

**DPST Summer Camp Research Project | April 2026 – Present**

## Overview

This research project investigates machine learning approaches for predicting the Remaining Useful Life (RUL) of turbofan engines using the NASA C-MAPSS dataset.

The study explores GRU-based models and Kalman Filtering to improve prediction performance and stability, with an emphasis on predictive maintenance applications.

## Research Objectives

- Develop machine learning models to predict the remaining useful life of turbofan engines.
- Explore GRU-based models for learning temporal patterns in engine degradation data.
- Investigate Kalman Filtering for sensor data processing and prediction stability.
- Evaluate model performance across four NASA C-MAPSS subsets.

## Dataset

The study uses the **NASA C-MAPSS Turbofan Engine Degradation Dataset**, which contains engine sensor measurements for degradation modeling and RUL prediction.

The experiments cover four subsets:

- FD001
- FD002
- FD003
- FD004

The dataset is not included in this repository.

## Methodology

The research workflow consists of seven phases:

1. **Data Overview** — Examine the dataset structure and sensor measurements.
2. **Data Cleansing & Target Generation** — Prepare the data and generate RUL target values.
3. **Operating Conditions & Per-Condition Normalization** — Analyze operating conditions and normalize sensor measurements accordingly.
4. **Scalar Kalman Filter** — Apply scalar Kalman filtering within the data processing pipeline.
5. **Feature Analysis & Final Scaling** — Analyze sensor features and perform final scaling.
6. **Model Training** — Train machine learning models for RUL prediction.
7. **Model Evaluation** — Evaluate model performance using RMSE and the NASA scoring function.

## Experimental Results

The reported experimental results across the four C-MAPSS subsets are summarized below.

| Dataset | RMSE | NASA Score |
|:---|---:|---:|
| FD001 | 12.74 | 280 |
| FD002 | 12.55 | 777 |
| FD003 | 13.61 | 572 |
| FD004 | 15.07 | 1,170 |

**Evaluation metrics:**
- **RMSE (Root Mean Squared Error):** Measures the magnitude of prediction errors. Lower values indicate better predictive accuracy.
- **NASA Score:** Evaluates prediction performance using an asymmetric penalty for prediction errors.

These results represent the reported performance of the evaluated models on each subset.

## Research Support

- **Research Program:** DPST Summer Camp
- **Research Funding:** THB 10,000
- **Research Period:** April 2026 – Present
- **Academic Advisors:** Faculty advisors from Chiang Mai University and Thammasat University

## Applications

Remaining Useful Life prediction is relevant to predictive maintenance, where estimates of equipment degradation can help inform maintenance planning and reduce unexpected equipment failures.

## Repository Scope

This repository provides a high-level overview of the research objectives, methodology, and approved experimental results.

Source code, datasets, and additional research materials are not included. Further details may be shared subject to research approval and applicable publication or funding requirements.

## Acknowledgment

This research was supported by the DPST Summer Camp program. The author acknowledges the academic guidance provided by faculty advisors from Chiang Mai University and Thammasat University.
