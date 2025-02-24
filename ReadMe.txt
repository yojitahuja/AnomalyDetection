# Anomaly Detection in Time Series Data

## Project Overview
This project focuses on anomaly detection in time-series data using Local Outlier Factor (LOF) and Isolation Forest models. The workflow includes data preprocessing, exploratory data analysis (EDA), and model-based anomaly detection techniques.

## Repository Structure



NOTE: DataAnalysis.ipynb is not a part of this assignment, it is a rough notebook 
        for me to compare the steps I have perforemed and to play around. 
        but you can go through it if you wish to understand what I did.


FUNCTIONS  ->

1. DATALOADER:
    read excel file data 
    pre processes the Data 
    Cleans the Data
    Fill missing values 
    Makes new excel for the clean data

2. EDA (Exploratory Data Anlysis)
    Plots the data of each feature against time 
    Performed ADFuller test 
    Resideual decompse into season, Resideual and trends 
    Finds Correlation between the features 

3. LOF:
    implements Local Outlier Factor Model on each faeture 
    fits and predicts on the data 
    Graph plotted with anomaly points in feature seperately 

4. IsolationForest:
    implements IsolationForest Model on each faeture 
    fits and predicts on the data 
    Graph plotted with anomaly points in feature seperately 
    Model did work well with the provided data even after finetuning it in multiple ways. 

NOTE: Please not that due to time and computional restreictions Models are not perfectly trained 
        There is always scope improvement. 

PPT attached in the file it self

Best Regards, 
Yojit Ahuja
