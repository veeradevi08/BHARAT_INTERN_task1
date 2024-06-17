# SMS Spam Classifier

This repository contains a Jupyter Notebook that implements an SMS spam classifier using a Multinomial Naive Bayes model. The project involves data preprocessing, text vectorization using TF-IDF, model training, and evaluation. Additionally, an interactive feature is provided to allow real-time predictions.

## Dataset

The dataset used is a collection of SMS messages labeled as 'spam' or 'ham' (non-spam).

## Steps Involved

1. **Data Preprocessing:** Cleaned and prepared the dataset.
2. **Text Vectorization:** Used TF-IDF Vectorizer to convert text data into numerical format.
3. **Model Training:** Trained a Multinomial Naive Bayes classifier on the vectorized data.
4. **Model Evaluation:** Evaluated the model's performance on the test set.
5. **Saving Models:** Saved the trained model and TF-IDF vectorizer for future use.
6. **Interactive Feature:** Added an input prompt for real-time spam prediction.

## Files

- `spam.csv`: The dataset file.
- `spam_classifier.pkl`: The trained Naive Bayes model.
- `tfidf_vectorizer.pkl`: The TF-IDF vectorizer.
- `sms_spam_classifier.ipynb`: Jupyter Notebook with the complete code.

## How to Run

1. Clone the repository.
2. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook to see the code and outputs.
4. Use the provided input prompt to make real-time predictions.

## Requirements

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- pickle

## Project Description

This project is designed to demonstrate text classification techniques using natural language processing. The main goal is to accurately classify SMS messages as spam or non-spam using a machine learning model. The project showcases the importance of data preprocessing and feature extraction in building effective machine learning models. The addition of an interactive feature allows for real-time predictions, making the project more interactive and practical.

Feel free to explore the code and provide any feedback or suggestions!
