# Claim-Insurance-Data-Analysis

In this machine learning project, we aim to leverage advanced analytical techniques to extract
meaningful insights and predictions from a given dataset. Through a systematic process of
exploratory data analysis, preprocessing, and modeling, our objective is to develop a robust
predictive model that enhances decision-making and understanding within the target domain.

Problem Statement
Dataset Name - Car Insurance Claim Prediction
https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification

Dataset Info - The Dataset contains information on policyholders having the attributes like policy
tenure, age of the car, age of the car owner, the population density of the city, make and model
of the car, power, engine type, etc, and the target variable indicating whether the policyholder
files a claim in the next 6 months or not.

Data Size - 58592 rows and 44 columns
Target Variable - Predict whether the policyholder will file a claim in the next 6 months or not.
There is a boolean column - is_claim which tells whether the insurance was claimed or not. Our
aim is to train the model to predict this given rest of the information. So, basically it is a binary
classification problem.

Proposed Solution
In this machine learning project, the analysis begins with a comprehensive exploratory data
analysis (EDA) phase, aimed at gaining insights into the dataset's structure, distributions, and
potential patterns. 
Following the EDA, the focus shifts to data preprocessing, where critical steps such as handling missing values, encoding categorical variables, and addressing
outliers are undertaken to ensure the data is appropriately formatted for modeling.  A key element of this preprocessing stage involves feature selection, wherein relevant features are identified to enhance model performance and reduce dimensionality using correlation matrix
and PCA. Subsequently, normalization is applied to standardize the feature values, ensuring
that each variable contributes uniformly to the model, thereby preventing any single feature from
disproportionately influencing the results. 
Finally, the modeling phase involves selecting and training machine learning models on the preprocessed data, evaluating their performance, and
fine-tuning as necessary to achieve the optimal predictive outcomes. This systematic approach,
from EDA to normalization and feature selection, culminates in the development of a robust and
effective machine learning model for the given dataset.
