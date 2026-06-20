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

## Robustness Validation
5-fold cross-validation confirms the binary 
classification result is stable and not a 
product of a single favorable split:

| Fold | Accuracy |
|------|----------|
| 1 | 99.97% |
| 2 | 100.00% |
| 3 | 99.99% |
| 4 | 100.00% |
| 5 | 100.00% |
| **Mean** | **99.99% ± 0.0133%** |

Duplicate analysis: 35 exact duplicates (0.06%) 
and 17 train/test overlapping rows (0.098%) were 
identified and disclosed transparently.

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
