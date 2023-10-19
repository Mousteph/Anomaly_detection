# Anomaly Detection

## Overview

This project focuses on anomaly detection using machine learning models applied to the UGR'16 dataset, specifically the [July 2016 dataset](https://nesg.ugr.es/nesg-ugr16/july.php#INI). For our analysis, we used a sample of the dataset, selecting one out of every 50 lines for efficiency.

## Project Description

This project aims to detect anomalies within the provided dataset using three different machine learning models, namely Isolation Forest, One-Class SVM, and XGBoost. The results indicate the performance of each model on both the training and test sets. These metrics serve as a benchmark for understanding the effectiveness of each method in identifying anomalies in the data.

## Models and Results

| Model           | Train Set Balanced Accuracy | Train Set Precision | Train Set Recall | Train Set R2 | Train Set F1 Score | Test Set Balanced Accuracy | Test Set Precision | Test Set Recall | Test Set R2 | Test Set F1 Score |
|-----------------|--------------------|---------------------|------------------|-------------|--------------------|------------------|-------------------|----------------|------------|-------------------|
| Isolation Forest| 49.36%             | 0.42%               | 0.74%            | -1.79       | 0.53%              | 49.43%           | 0.48%             | 0.86%          | -1.82      | 0.61%             |
| One-Class SVM   | 71.23%             | 2.28%               | 91.94%           | -38.98      | 4.45%              | 68.78%           | 1.93%             | 85.98%         | -43.43     | 3.77%             |
| XGBoost         | 99.99%             | 97.73%              | 100.00%          | 0.98        | 98.85%             | 99.73%           | 97.02%            | 99.50%         | 0.96       | 98.25%            |

## Dataset

The dataset used in this project is the [July 2016 dataset](https://nesg.ugr.es/nesg-ugr16/july.php#INI) from the UGR'16 dataset, sampled for efficiency in the analysis.
