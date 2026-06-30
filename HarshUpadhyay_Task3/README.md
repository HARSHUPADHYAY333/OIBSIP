#   Task 3

# Email Spam Detection

# Project Overview

This project focuses on building a Machine Learning model that can classify emails as Spam or Not Spam. Spam emails often contain unwanted advertisements, phishing attempts, or fraudulent content. The goal of this project is to automatically identify such emails and improve email filtering.

The model uses Natural Language Processing techniques to analyze email text and classify messages accurately.

# Objective

The main objective of this project is to develop a Machine Learning model that can detect spam emails based on their content and classify them into:
Spam and Not Spam (Ham)


## Dataset

The dataset contains email messages along with their labels.

| Column | Description |
|----------|------------|
| Label | Spam or Ham |
| Message | Email Text Content |


# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


# Machine Learning Algorithm

The following techniques were used:
 TF-IDF Vectorization
 Multinomial Naive Bayes

TF-IDF converts email text into numerical features, while Naive Bayes performs the classification task.


# Project Workflow

### 1. Data Loading
The email dataset was loaded using Pandas.

### 2. Data Cleaning
Unnecessary columns were removed and the dataset was prepared for training.

### 3. Data Exploration
The distribution of Spam and Ham emails was analyzed.

### 4. Feature Extraction
Email text was converted into numerical form using TF-IDF Vectorization.

### 5. Train-Test Split
The dataset was divided into training and testing sets.

### 6. Model Training
A Multinomial Naive Bayes model was trained using the training data.

### 7. Model Evaluation
The model was evaluated using:
Accuracy Score
 Classification Report
 Confusion Matrix


## Results
The model successfully classified emails into Spam and Not Spam categories with high accuracy.
The trained model was able to correctly identify most spam emails while minimizing incorrect classifications.

## Conclusion
This project demonstrates the practical application of Machine Learning and Natural Language Processing techniques in email spam detection.
The model achieved strong performance and can be used as a basic spam filtering system for email classification.



