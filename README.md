# MNCH-Dropout-Prediction
A comparative analysis of machine learning models in the prediction of dropout from the Maternal, Newborn and Child Healthcare (MNCH) Continuum in Kenya.
---  
# MNCH Dropout Prediction using Machine Learning  
## Background Of the Study  
- For optimal health, the maternal, newborn, and child healthcare (MNCH) continuum necessitates that the mother/child receive the full package of antenatal, intrapartum, and postnatal care. In sub-Saharan Africa,which Kenya is part of, dropping out from the MNCH continuum remains a challenge. Using machine learning, the study sought to forecast the MNCH continuum
drop out and determine important predictors in Kenya.
- **Dropout**, in this context, refers to the untimely discontinuation of healthcare engagement by pregnant women, mothers, newborns, or children before the completion of the recommended course of care. These dropouts disrupt the continuity of healthcare services and create a significant impediment to achieving improved maternal and child health outcomes.  

- This project uses machine learning techniques to predict dropout from the Maternal, Newborn, and Child Healthcare (MNCH) continuum in Kenya using data from the 2022 Kenya Demographic and Health Survey (KDHS). It also compares Random Forest and XGBoost performances in predicting dropout in the MNCH continuum.
---  

## Project Context
This project was undertaken as part of a group assignment for my final year undergraduate research. While the project was collaborative, the code in this repository also reflects my individual contributions, particularly in data cleaning, model development using Python (Random Forest and XGBoost), and result visualization.

## Project Objectives
## General Objective
To compare the predictive models for dropout within the MNCH continuum in Kenya using Machine Learning.  

## Specific Objectives  
1. To fit a predictive model for dropout within the MNCH continuum in Kenya using random forest and XGBoost.
2. To evaluate the performance and accuracy of the predictive model in identifying MNCH dropout cases.
3. To perform feature importance to identify significant determinants of MNCH dropouts to support data-driven health policy and intervention planning.

## Dataset
The analysis uses the KDHS 2022 women's dataset. For confidentiality, the original dataset is not included.  

## Statistical analysis  
- Using python 3.10, data cleaning was performed to prepare the dataset for analysis. Machine learning predictive models were built and trained in Python 3.10 using Kenya demographic Health Survey (2022) surveys data.  
- The Machine learning analysis utilized the classification method. The datasets were randomly assigned to the training and testing datasets using an 80/20 % split.
- The training data consisted of the data used to develop the models and the test data sets were used for evaluating the performance of the models.  
- Two classification algorithms namely the Random Forest and extreme XGBoost were employed.  

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Data visualization: Matplotlib, Seaborn
- Model evaluation: Accuracy, F1-score, Recall, Specificity, Confusion Matrix

## Instructions
1. Clone the repository
2. (Optional) Create a virtual environment
3. Install dependencies using `pip install`
4. Run the python script in Jupyter notebook or Google colab

## Author
Prissy Makena
