# Twitter Sentiment Analysis Using NLP

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify tweets into three sentiment categories: **Positive, Negative, and Neutral**.

The goal is to analyze text data and predict the sentiment expressed in tweets.

## Technologies Used

- Python
- Pandas and NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorization
- Matplotlib and Seaborn

## Project Workflow

1. **Data Exploration:** Analyzed sentiment distributions, missing values, and duplicate tweets.
2. **Text Preprocessing:** Applied text cleaning, tokenization, and lemmatization.
3. **Feature Extraction:** Converted cleaned tweets into numerical features using TF-IDF with unigrams and bigrams.
4. **Model Training:** Trained Multinomial Naive Bayes and Logistic Regression classifiers.
5. **Model Evaluation:** Evaluated accuracy, precision, recall, F1-score, and confusion matrices.
6. **Hyperparameter Tuning:** Used GridSearchCV with 5-fold cross-validation to tune Logistic Regression.

## Model Performance

| Model | Test Accuracy | Test Macro F1 |
|---|---|---|
| Multinomial Naive Bayes | 63.74% | 63.03% |
| Logistic Regression | 68.13% | 68.48% |

**Best cross-validation macro F1:** 69.05% (Logistic Regression, `C=1`, `class_weight='balanced`).

Cross-validation and test metrics were calculated on different data splits and should not be interpreted as directly equivalent.

## Key Learnings

- Preparing unstructured text for Machine Learning.
- Applying TF-IDF feature extraction.
- Comparing classification algorithms.
- Evaluating multiclass classification performance.
- Performing hyperparameter tuning.

## How to Run

1. Clone or download the repository.
2. Install the required dependencies.
3. Download the original Twitter dataset.
4. Update the dataset path in the notebook.
5. Run the notebook cells in order.

## Future Improvements

- Evaluate Linear SVM and other text classification models.
- Improve handling of emojis and sarcasm.
- Perform additional error analysis.
- Build a Streamlit application for interactive sentiment prediction.

## Author

**Hazem Ahmed Wageh**

Computer Science Student | Aspiring Data Scientist

[GitHub Profile](https://github.com/hazemah55)
