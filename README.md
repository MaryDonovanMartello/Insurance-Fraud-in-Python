# Insurance-Fraud-in-Python
## EDA and Classification

### Summary

The goal of this project was to use Python to identify significant features in fraudulent insurance claim transactions and to design predictive classification models to predict whether fraud was reported on the insurance claim transaction. The project addressed the imbalanced target variable by weighting the classes. Logistic Regression, Support Vector Machine Classification, and Random Forest models were tested. The paper walks through the data understanding and preparation, different models tested, methodology, and evaluation of the project.

### Tools

* Scikit-learn
* Seaborn
* Matplotlib
* Yellowbrick
* Numpy
* Pandas
* Scipy
* Patsy
* Tabulate
* Counter

**Data:** [claims](https://www.kaggle.com/patilk1/fraudulentinsuranceclaim)

### Methodology

Compared multiple versions of models that varied techniques for data-splitting, the imbalanced target variable, and feature selection.

### Models / Methods / Metrics

* Random Forest
* Logistic Regression / LASSO Logistic Regression
* Support Vector Classification
* Principal Component Analysis
* Log-Transformation and Scaling
* GridSearch
* Recall

## Project Preview

### Exploratory Data Analysis

This project utilized the EDA from this Exploratory Data Analysis and Hypothesis Testing project: [EDA.](EDA-and-Hypothesis-Testing)

### Principal Component Analysis

PCA was implemented because of multicollinearity between groups of input variables.

### Evaluation

![RESULTS1](/images/Results.PNG)

**Notebooks**

1_EDA_Prep
This notebook includes the EDA, data preparation and PCA.

2_R_Visuals
This file includes EDA visuals and the R code that produced them.

3_Feature_Selection
This notebook includes feature selection models.

4_Baseline_Model
This notebook includes a baseline logistic regression model for comparison to more complex models.

5_Test_Subsets_of_Features
This notebook tests for best subsets of features with a logistic regression model.

6_Logistic_Regression
This notebook includes the Logistic Regression Model’s model evaluation and selection and metric evaluation.

7_LASSO_Regression_Model
This notebook includes the LASSO Logistic Regression Model’s model evaluation and selection and metric evaluation.

8_Support_Vector_Machine
This notebook includes the Support Vector Machine Model’s model evaluation and selection and metric evaluation.

9_Random_Forest_Model
This notebook includes the Random Forest Model’s model evaluation and selection and metric evaluation.
