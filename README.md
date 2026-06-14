# QSAR-SERT-Inhibitors
QSAR modeling for serotonin transporter inhibitors - Final project

*Please open file "finalproject.py" to view the code.*

# QSAR Modeling for SERT Inhibitors

## Original Paper
This project is based on the paper by **Veselinović et al. (2026)**:
> "QSAR-Guided Design of Serotonin Transporter Inhibitors Supported by Molecular Docking and Biased Molecular Dynamics"
> *Pharmaceuticals*, 19(3), 444.

The original study includes 50 compounds. In this project, the main design series (A to A8, 9 compounds) was used for QSAR modeling.

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
- `finalproject.py` - Python source code (full implementation)
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

## Supervisor
Dr. Mohammad Mehdi Keikha

## University
University of Sistan and Baluchestan

## Date
June 2026

## Acknowledgments
Special thanks to Veselinović et al. (2026) for providing the molecular structures and activity data used in this project.
