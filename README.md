# QSAR-SERT-Inhibitors
QSAR modeling for serotonin transporter inhibitors - Final project

# QSAR Modeling for SERT Inhibitors

## Overview
This project implements a complete QSAR pipeline for predicting serotonin transporter (SERT) inhibition activity of 9 compounds (series A to A8).

## Models Used
- Linear Regression
- Ridge Regression
- Random Forest (simple & tuned)
- SVM (RBF & tuned)
- Neural Network (1 & 2 layers)

## Key Results
- Best model: Random Forest (R² = 0.119, MAE = 0.137)
- Most important features: LogP (40%) and MolWt (35%)

## Files
- `finalproject.ipynb` - Complete Jupyter notebook with all code
- `QSAR_Final_Results.txt` - Final results of all models

## Requirements
- rdkit
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Author
Maryam Nekooei
Supervisor: Dr. Mohammad Mehdi Keikha
University of Sistan and Baluchestan, 2026
