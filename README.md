# PCOS-Data-Analysis-and-Visualization
This analysis will explore the relationship between various clinical, demographic, and lifestyle factors with the occurrence of PCOS and identifying patterns that may help in early detection and understanding of contributing factors for PCOS.
* Identifying  and handling any missing or NaN values in the dataset.
* Applying SMOTE to balance classes.
* Descriptive Analysis.
* Assessing relationships between features and their influence on PCOS.
*  Visualizing the distribution of key features.
*  Using clustering techniques like KMeans or hierarchical clustering to identify patterns or groups within the dataset.
*  Using a machine learning model like a Decision Tree or Random Forest to identify the most important features contributing to PCOS and visualize them using bar plots.


# PCOS Data Analysis and Balancing Project

## Overview
This project focuses on analyzing and preprocessing a dataset related to Polycystic Ovary Syndrome (PCOS). Key steps include handling missing values, balancing the dataset using SMOTE, and exploring feature relationships using a correlation matrix. The analysis provides insights into the influence of various features on PCOS.

## Key Features
- **Data Cleaning**: Handle missing and improperly formatted data.
- **Class Balancing**: Use Synthetic Minority Over-sampling Technique (SMOTE) to balance the target classes.
- **Feature Analysis**: Assess feature correlations and visualize relationships using heatmaps.
- **Scalable Pipeline**: Modular code for preprocessing, balancing, and analysis.

## Libraries Used
- `pandas` for data manipulation
- `numpy` for numerical operations
- `seaborn` and `matplotlib` for visualization
- `scikit-learn` for splitting data
- `imblearn` for SMOTE-based class balancing

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
