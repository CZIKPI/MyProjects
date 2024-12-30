# Bankruptcy Prediction Using Machine Learning
## Overview
This repository contains a machine learning project aimed at classifying whether a company is bankrupt based on selected financial ratios. 
The goal is to leverage various machine learning algorithms to predict the likelihood of bankruptcy for companies using historical financial data
## Project Structure
The Project is structured as follows:
- data/:  Directory containing the dataset used for training and testing the model.
- notebooks/: Jupyter notebooks illustrating the data exploration, feature engineering , and model training processes.
- scripts/:Python scripts for data preprocessing, model training and evaluation.
- models/: Saved models for deployment and further analysis.
- Results/: Directory for storing results and evaluation metrics
- README.md:This file

## Dataset 
The dataset used in this project consists of various financial ratios for multiple companies over a period of time.
The target variable indicates whether a company went bankrupt or not. Key financial ratios include:
- dvt: Dividends-Total
- ebit: Ernings before interest and taxes
- gp: Gross profit
- ni: Net income (Loss)
- oiadp: Operating income after depreciation
- dvpsx_f: Dividends per Share-Ex-Date-Fiscal
- revt: Revenue-Total
- mkvalt: Market value-Total-Fiscal

## Results 
The results of the model training and evaluation, including key metrics such as accuracy, precision, recall, and F1-score, are stored in the results/ directory. 
Visualization of model performance can be found in the Jupyter notebooks within the notebooks/ directory.
