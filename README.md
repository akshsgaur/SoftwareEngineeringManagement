# SoftwareEngineeringManagement
**Project Overview**
The project utilizes single-cell RNA sequencing data from the CELLxGENE Census, focusing on samples related to dementia and normal cognitive function. We employ a comprehensive data analysis pipeline that includes data preprocessing, quality control, feature selection, and machine learning modeling.
Key Features
Data integration from multiple single-cell RNA-seq datasets
Quality control and filtering of cellular data
Analysis of mitochondrial gene expression and dysfunction markers
Investigation of Alzheimer's disease progression using Braak staging
Machine learning models to identify key features associated with dementia.

**Data Sources**
The project uses three primary datasets from the CELLxGENE Census:

https://datasets.cellxgene.cziscience.com/3d690bcf-c9d3-4fcf-b7e1-e0e622bbf958.h5ad
https://datasets.cellxgene.cziscience.com/ee226a77-6ec1-4a16-b653-8cbacd3876bc.h5ad
https://datasets.cellxgene.cziscience.com/7bb8238f-b5a7-4bbd-9c00-244e2b72e140.h5ad

**Methodology**
Data Preprocessing:
Download and load datasets using the cellxgene_census library
Merge datasets and perform initial quality control
Filter cells based on gene detection, UMI counts, and mitochondrial gene expression
Feature Selection:
Identify common genes across datasets
Extract relevant clinical features (e.g., Braak stage, APOE4 status)
Exploratory Data Analysis:
Visualize data using dimensionality reduction techniques (PCA, t-SNE, UMAP)
Analyze distribution of mitochondrial gene expression across different disease stages
Machine Learning Modeling:
Apply Lasso regression for feature importance analysis
Implement other machine learning models to predict disease progression

**Statistical Analysis:**
Perform correlation analysis between clinical features and gene expression
Conduct statistical tests to compare different patient groups
***Requirements***
1. Python 3.x
2. Scanpy
3. Pandas
4. NumPy
5. Scikit-learn
6. Matplotlib
7. Seaborn
8. Cellxgene-census

***Usage***
Clone the repository

Install required packages: pip install -r requirements.txt

Run the Jupyter notebook or Python scripts to perform the analysis

**Results**

The project aims to:

Identify key genes and pathways associated with mitochondrial dysfunction in dementia

Develop predictive models for disease progression based on gene expression profiles

Provide insights into potential therapeutic targets for neurodegenerative diseases
