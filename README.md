# Spam-SMS-Detection
The objective of this project is to develop a machine learning model that can accurately classify SMS messages as either spam or non-spam (ham). The dataset consists of labeled text messages, where each message is categorized as spam (unwanted, promotional, or fraudulent) or ham (legitimate communication).
Key Steps Involved
## Data Preprocessing-

Removing punctuation, stopwords, and special characters

Checking the null values

Feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency) or Bag-of-Words (BoW)

## Exploratory Data Analysis (EDA)

Understanding the distribution of spam vs. ham messages

Oversampling method to remove class imbalance problem

## Model Training & Evaluation

Implementing ML algorithm called Logistic regression for training

Evaluating model performance using metrics like accuracy, precision, recall, F1-score, and AUC-ROC

## Expected Outcome
A highly accurate model capable of distinguishing between spam and legitimate messages.

A well-optimized model that minimizes false positives (misclassifying ham as spam) and false negatives (missing actual spam messages).

Deployment-ready solution for real-time SMS spam detection.
