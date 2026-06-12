# XGBoost-SHAP Malware Detection

## Overview
Binary malware detection framework using 
volatile memory forensics with XGBoost 
and SHAP explainability.

## Dataset
CIC-MalMem-2022 (Obfuscated-MalMem2022)
- Total records: 58,058
- Features: 55
- Classes: Benign, Malware

## Results
| Model | Accuracy |
|---|---|
| CNN-LSTM (baseline) | 83.89% |
| XGBoost (binary) | 100% |

## Requirements
- Python 3.10
- XGBoost
- SHAP
- TensorFlow
- scikit-learn
- pandas
- matplotlib
- seaborn

## How to Run
1. Open MalwareDetection_XGBoost_SHAP.ipynb
2. Run in Google Colab
3. Upload CIC-MalMem-2022 dataset
4. Run all cells

## Authors
- Himanshu Sahu — GH Raisoni IST University
- Neha Joshi — GH Raisoni IST University

## Paper
Explainable XGBoost Framework for Binary 
Malware Detection via Volatile Memory 
Forensics Using CIC-MalMem-2022 with 
SHAP Analysis
