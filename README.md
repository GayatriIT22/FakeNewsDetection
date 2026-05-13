# FakeNewsDetection
A machine learning-based system designed to identify and classify fabricated news articles using a Passive Aggressive Classifier. Features advanced NLP preprocessing and achieves over 89% accuracy on the WELFake dataset.
Fake News Detection System
Overview
This project implements a machine learning-based news classifier designed to identify fabricated or misleading news articles. Using a Passive Aggressive Classifier, the model analyzes linguistic patterns to distinguish between authentic and fake news with high precision.

Key Features
Advanced Text Preprocessing: Utilizes NLTK for stopword removal, lemmatization, and regex-based cleaning of URLs and HTML tags.

Feature Extraction: Implements TF-IDF Vectorization with N-Grams (range 1,2) to capture context and "breaking news" phrases.

High Performance: Achieved a Mean Accuracy of 90.94% through 5-fold cross-validation.

Model Persistence: Saves the trained model and vectorizer as .pkl files for instant deployment without retraining.

Tech Stack

Language: Python 3   

Libraries: Scikit-Learn, Pandas, NumPy, NLTK

Visualization: Matplotlib, Seaborn

Results
The model demonstrates robust performance, particularly in identifying "Fake" news accurately:

Accuracy: 89.29%

F1-Score (Fake News): 0.93

Stability: Standard Deviation of only 2.07% across cross-validation folds
