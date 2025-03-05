# Python_Projects

## 1. Resume Classification Using Text Mining

### Overview

This project focuses on classifying resumes into 24 different job categories using text mining and machine learning techniques. The goal is to develop a multi-class classification model that accurately predicts job categories based on resume content.

### Dataset

The dataset consists of:

ID: Unique identifier for each resume.

Resume_str: The textual content of resumes.

Resume_html: HTML representation of resumes.

Category: The target variable indicating job classification.

### Steps Involved

#### Data Preprocessing

* Removing special characters, punctuation, and unnecessary elements.

* Handling missing values.

* Text normalization and tokenization.

#### Exploratory Data Analysis (EDA)

* Analyzing category distribution.

* Identifying the most common job categories.

* Visualizing text characteristics.

#### Feature Engineering

* Converting text into numerical representations (TF-IDF, Word Embeddings, etc.).

* Selecting the most relevant features for classification.

#### Model Building & Evaluation

* Training multi-class classification models (Naïve Bayes, Random Forest, Deep Learning models, etc.).

* Evaluating models using accuracy, precision, recall, and F1-score.

* Analyzing confusion matrices to determine the best-performing model.

### Key Insights

Category Distribution: BUSINESS-DEVELOPMENT and INFORMATION-TECHNOLOGY have the highest number of resumes, while BPO has the least.

Text Cleaning Impact: Removing extraneous characters and stopwords significantly improves model accuracy.

Feature Representation: TF-IDF and Word Embeddings play a crucial role in text classification accuracy.

## 2. Customer Churn Prediction

### Overview

This project focuses on predicting customer churn using data analysis and machine learning techniques. The dataset includes customer demographics, transaction behavior, and credit-related metrics. The goal is to identify key factors influencing churn and develop predictive models to mitigate customer attrition.

### Dataset

The dataset consists of various customer attributes, including:

Customer demographics (Age, Gender, Education, Marital Status, Income Category)

Credit behavior (Credit Limit, Utilization Ratio, Transactions, Inactive Months)

Churn Indicator (Target Variable)

### Steps Involved

#### Data Preprocessing

* Removing unnecessary columns

* Checking for missing values and duplicates

#### Exploratory Data Analysis (EDA)

* Distribution of customer attributes

* Correlations between features

* Visualization of key trends

#### Feature Engineering

* Identifying significant features affecting churn

* Handling categorical and numerical variables

#### Model Building & Evaluation

* Training predictive models (e.g., Decision Tree, Gradient Boosting, XGBoost, Random Forest, Bagging Classifier)

* Evaluating model performance using accuracy, precision, recall, and F1-score

### Key Insights

Credit Limit vs. Utilization Ratio: Customers with higher credit limits tend to have lower utilization ratios.

Churn Trends: Customers with high utilization ratios and lower income categories are more likely to churn.

Demographic Impact: Age and marital status influence churn probability.

### Model Performance & Conclusion

Based on the evaluation metrics:

Optimized XGBoost performed the best with the highest recall (0.9375), accuracy (0.9668), and F1-score (0.9020), making it the most effective model for predicting churn.

Optimized Gradient Boosting and Optimized Random Forest also performed well, but XGBoost showed superior balance between precision and recall.

Optimized Bagging Classifier had a strong precision score but slightly lower recall.

Optimized Decision Tree had the lowest precision and F1-score among the models.

Thus, XGBoost is recommended as the best model for churn prediction in this dataset.

Best Model: The most effective model for resume classification is determined based on confusion matrix results.
