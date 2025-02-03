# CFA Analytics Induction Task 2025
## Overview
The goal of the project is to conduct exploratory data analysis (EDA) on a given IPL Auction Dataset. The dataset, after cleaning, was manipulated to extract underlying patterns and insights, which are visualised by graphical methods where possible. The EDA project also contains ML techniques such as KMC and Linear Regression.

## File Structure
The GitHub Repository contains the following key files
- `final_dataset.csv`: The raw dataset provided by the CFA Club
- `edaNotebook.ipnyb`: A systematic JupyterNB containing steps from the EDA
- `prelim.ipynb`: A rough JupyterNB containing a preliminary and unstructured attempt at EDA
- `240005009_EDAReport_ArhamAneeq.pdf`: A PDF report consisting of more structured insights into the data and patterns underlying it

The main file here is the PDF, including most of the final result of the EDA with my understanding of the dataset. The JupyterNB `edaNotebook.ipynb` consists of code which generated most of the statistics and visuals present in the PDF, and is well structured with headings and relatively readable code.

The `prelim.ipynb` lacks clear structure, but includes far more graphs and statistics than present in either of the other two files. It includes attempts at further methods of data visualisation, such as Waffle Charts or Network Graphs, and also an ML model known as Random Forests, all of which I deemed not fit for inclusion in the the final files. The code in this notebook is also less readable, and consists of frankly horrendous uses of lambdas and hodgepodge programming.

## Requirements

To run the analysis, you will need to the following Python Libraries
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `sklearn`
- `scikit_posthocs`
- `networkx` (optional)
- `pywaffle` (optional)

You will need Jupyter to run the notebooks.