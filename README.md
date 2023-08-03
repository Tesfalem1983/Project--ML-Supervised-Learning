# Project - Supervised Learning

## Project Goals:
#### - Applying supervised learning techniques to a Diabetes data set and use data visualization tools to communicate the insights gained from the analysis.

## Process:
### Step 1: Explanatory Data Analysis:
By creating visualizations and statistical summary  to spot abnormal distribution & outliers.
### Step 2: Data Cleaning 
Replacing zero values with mean of the columns for all the feature columns.
### Step 3:  Preprocessing & Feature Engineering
- Normalizing the distribution for the skewed distribution in Age &  Diabetes Pedigree Function through logarithimic transformation.
- Scaling data in order to avoid dominance of one feature over the other.
- Handling the binary class imbalance in the column to be predicted to avoid misleading our model training to favour one over the other.
### Step 4 : Training & Evaluating our model
- Training model through both logistic regression and Random forest aligorithms.
- Evaluating both models through different metrics that include accuracy, precision, and F1-score.
### Step 5 : Compare both Model results
Compare both models on the results of the evaluation metrics
### Step 6 : Communicate overall insights in bullet points.
- Convey the most important insights from the EDA and both models in bullet points  to stakeholders and decision makers.

## Findings:
1. The distribution for Diabetes Pedigree Function and Age were skewed. Took action to improve the distribution to avoid misleading our model training.
2. There was significant imbalance in our outcome variable`(**binary classification of ratio of approximately 35% to 65%**)` which can potentially lead our model to favor into negative diabetes outcome). This is very dangerous outcome in this type of scenario as this will give false negative(meaning will give an outcome of negative diabetes to patients that have diabetes).
3. Noticed outliers in **Insulin & Skin thickness**.
4. Both models generally **performed okay**  and with **hyperparamater tunning** they can perform better.
5. Random Forest model has slightly better performance in the accuracy and precision metrics
6. Training, a model to determine whether a patient is positive or negative is very sensitive and delicate matter  and especially if a hospital or medical center is to depend primarly on the result of ML model. This requires extremely quality data, thorough preprocessing and feature engineering. Generally The prediction of the model should surpass the normal six sigma quality.

## Challenges & Future Goals:
- Choosing the right method to solve the class imbalance given that we have limited data(768 sample data)
- If I had more time, I could have tried  other ML models to see how they perform in the dataset. Moreover I would play more in tableau to make more interesting visualizations.
