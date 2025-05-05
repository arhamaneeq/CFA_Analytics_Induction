# CFA Analytics Induction Task 2025
## Overview
This project presents an exploratory data analysis (EDA) of an IPL Auction dataset, as part of the CFA Analytics Induction Task for 2025. The analysis aims to uncover meaningful insights and trends within the dataset through data cleaning, statistical exploration, and visualization. The final deliverable includes not only EDA techniques but also an introduction to machine learning methods such as K-Means Clustering (KMC) and Linear Regression.

## Repository Structure
The GitHub Repository contains the following key files
- `final_dataset.csv`: The raw dataset provided by the CFA Club, uncleaned
- `edaNotebook.ipnyb`: A well-organized Jupyter notebook that systematically presents the EDA process. It includes the code used to generate statistics and visualizations referenced in the final report.
- `prelim.ipynb`: An exploratory notebook capturing early-stage, unstructured analysis. While less readable and loosely organized, it contains numerous experimental visualizations (e.g., Waffle Charts, Network Graphs) and a Random Forest model that were ultimately excluded from the final report.
- `240005009_EDAReport_ArhamAneeq.pdf`: A formal report summarizing key findings, visual insights, and interpretation. This document serves as the primary reference for the final analysis.

The primary deliverable is the PDF report, which consolidates the final insights. The `edaNotebook.ipynb` supports it with reproducible code and visuals, while `prelim.ipynb` documents the exploratory journey and alternative modeling attempts.

## Key Principles

- `Exploratory Data Analysis`: A structured approach to identifying patterns, anomalies, and relationships in raw auction data.
- `Data Cleaning & Transformation`: Null handling, feature engineering, and dataset reshaping to ensure analytical robustness.
- `Statistical visualisation`: Insightful graphical summaries using bar plots, heatmaps, pair plots, and custom visual styles.
- `Machine Learning Integration`: Application of clustering and regression models to quantify trends and predictive patterns.
- `Analytical Reporting`: A concise yet comprehensive report that integrates findings, visual evidence, and interpretation.

### Features
- Cleaned and structured dataset with standardised player and team metadata.
- Rich data visualisation including price distributions, roll-wise trends, and team level comparisons.
- K-Means Clustering and Principal Component Analysis to explore multivariate relationships between player attributes and auction price.

## Dependencies

To run the analysis, you will need to the following Python Libraries
- `pandas`, `numpy`, `scipy`: data manipulation & statistical inference
- `matplotlib`, `seaborn`, `pywaffle`, `networkx` - visualisation (`pywaffle` and `networkx` are optional)
- `scikit-learn`, `scikit-posthocs` - machine learning & post-hoc testing

The Analysis is designed to be run in a `Jupyter` Notebook.


### Notes

- The project reflects both the structured analytical process and the underlying iterative experimentation inherent to data analytics.
- Optional dependencies were used for experimental visualisation and are not required to reproduce the main results.
