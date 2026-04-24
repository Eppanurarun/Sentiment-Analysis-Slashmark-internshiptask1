# Sentiment-Analysis-Slashmark-internshiptask1
Sentiment Analysis on Restaurant Reviews using NLP and Multinomial Naive Bayes for Positive and Negative Review Classification
# Sentiment Analysis on Restaurant Reviews

## Project Overview

This project performs Sentiment Analysis on restaurant reviews using Natural Language Processing (NLP) and Machine Learning. The main objective is to classify customer reviews as Positive or Negative based on the review text.

This helps businesses understand customer feedback and improve service quality.

---

## Problem Statement

Customer reviews contain valuable feedback about restaurant services and food quality. Manually analyzing large numbers of reviews is difficult and time-consuming.

This project uses NLP techniques and Machine Learning to automatically predict whether a review expresses a positive or negative sentiment.

---

## Dataset Used

### Dataset Name:
Restaurant_Reviews.tsv

### Dataset Description:

The dataset contains 1000 restaurant reviews with two columns:

- **Review** → Customer review text
- **Liked** → Sentiment label

### Label Meaning:

- **1** = Positive Review
- **0** = Negative Review

---

## Technologies Used

- Python
- Google Colab
- Machine Learning
- Natural Language Processing (NLP)

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- re
- scikit-learn

---

## NLP Techniques Used

### Text Preprocessing

- Removing special characters using Regular Expressions
- Converting text to lowercase
- Removing stopwords
- Applying stemming using PorterStemmer

### Feature Extraction

- CountVectorizer (Bag of Words Model)
- max_features = 1500

---

## Machine Learning Model Used

### Algorithm:
Multinomial Naive Bayes Classifier

This algorithm is used for text classification and works effectively for sentiment analysis tasks.

---

## Model Training Process

1. Load dataset
2. Clean and preprocess text data
3. Convert text into numerical vectors
4. Split dataset into training and testing sets
5. Train model using Multinomial Naive Bayes
6. Predict test data
7. Evaluate model performance

---

## Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- Confusion Matrix
- Heatmap Visualization

---

## Hyperparameter Tuning

Different alpha values were tested to improve model performance.

The best alpha value was selected for better accuracy and prediction quality.

---

## Sample Predictions

Example reviews tested:

- "Amazing food and excellent service" → Positive
- "Worst restaurant experience ever" → Negative
- "Food was average but staff was polite" → Prediction based on sentiment

---

## Final Conclusion

The model successfully predicts whether a restaurant review is positive or negative using NLP and Machine Learning.

Multinomial Naive Bayes performed well for this text classification problem. This project demonstrates how customer feedback can be automatically analyzed for business improvement.

This system can be extended for larger review platforms like Zomato, Swiggy, and Google Reviews.

---

## Author

Internship Project Submission

Machine Learning Internship Project
