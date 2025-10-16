# Machine-learning-Project-on-fake-news-detection
A Python-based machine learning project for detecting fake news using Naive Bayes and Support Vector Classifier (SVC) with TF-IDF text features.  This repository contains a complete Fake News Detection pipeline implemented in Python, using Natural Language Processing (NLP) and Machine Learning techniques.

## Key Features
- Data preprocessing, including text cleaning and tokenization.
- Handling class imbalance using oversampling techniques.
- Feature extraction with TF-IDF (unigrams and bigrams).
- Two classification models:
  - Multinomial Naive Bayes (NB) – fast baseline model.
  - Support Vector Classifier (SVC) – high-accuracy model with class balancing.
- Evaluation using Accuracy, F1-Score, and Confusion Matrix.
- Customizable probability thresholds for improving prediction reliability.
- Ensemble option to combine NB and SVC for better real-world performance.

## Use Case
Automatically classify news articles as **Real** or **Fake**, useful for social media monitoring, news verification, and research applications.

## Tech Stack
- Python 3.x
- scikit-learn
- pandas & numpy
- matplotlib & seaborn (for visualization)
- Streamlit (for deployment)
