# White Wine
This project was completed in part of the requirements of the Big Data & Predictive Analytics Certificate Program at Toronto Metropolitan University. 

### 1. Dataset Source: 
- White Wine Quality Data Set. Available from the UCI machine learning repository (https://archive.ics.uci.edu/ml/datasets/wine+quality)
- Dataset Overview: One dataset is used relating to north Portuguese white wine samples. The goal is to use white wine samples to model white wine quality based on physicochemical tests.

- Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

### 2. Problem Definition & Target Variable: 
The goal of this project is to identify which chemical variables are the best predictors for a quality white wine. To be more specific, we outline below the intent for this analysis:
- Demonstrate the contribution of each feature to the wine quality in our model
- Demonstrate which variables are most relevant in identifying wine quality
- Demonstrate which features are less important in determining the wine quality as mentioned earlier, our target variable will be wine quality, which will be transformed into a two factor ordinal variable where wine is either “good” (quality score is >5) or “bad” (quality score is <=5)

### 3. Project Relevancy: 
 The current wine industry standard is to use product quality certifications to promote their products. Wine’s product quality certifications are comprised of physicochemical and sensory tests. Physicochemical tests are laboratory-based and consider factors like chlorides, acidity, and additional physicochemical properties. Sensory tests are performed by highly qualified human experts, which makes this process costly, time-consuming, and inexact. Understanding how, and if, the human quality of tasting can be related to white wine’s physicochemical properties would help make quality certifications more predictable, which is of interest to all white wine stakeholders.

### 4. Proposed Data Techniques: 
- EDA
- Logistic Regression Modeling
- Multinomial Logistic Regression Modelling 
- Decision Trees
- Random Forest

### 5. Files included
- Data set: winequality-white.csv
- List of R-codes: Indv_Proj.Rmd





