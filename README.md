# Python_Projects

## Resume Classification Using Text Mining

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

Removing special characters, punctuation, and unnecessary elements.

Handling missing values.

Text normalization and tokenization.

#### Exploratory Data Analysis (EDA)

Analyzing category distribution.

Identifying the most common job categories.

Visualizing text characteristics.

#### Feature Engineering

Converting text into numerical representations (TF-IDF, Word Embeddings, etc.).

Selecting the most relevant features for classification.

#### Model Building & Evaluation

Training multi-class classification models (Naïve Bayes, Random Forest, Deep Learning models, etc.).

Evaluating models using accuracy, precision, recall, and F1-score.

Analyzing confusion matrices to determine the best-performing model.

### Key Insights

Category Distribution: BUSINESS-DEVELOPMENT and INFORMATION-TECHNOLOGY have the highest number of resumes, while BPO has the least.

Text Cleaning Impact: Removing extraneous characters and stopwords significantly improves model accuracy.

Feature Representation: TF-IDF and Word Embeddings play a crucial role in text classification accuracy.

Best Model: The most effective model for resume classification is determined based on confusion matrix results.
