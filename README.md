# Spam News Classifier

A Python project to classify news articles as **spam/fake** or **real/legitimate** using machine learning.

## Features

- Text preprocessing
- Spam/Fake news classification
- Model evaluation with accuracy, precision, recall, and F1-score

## Project Structure

SpamNewsClassifier/
├── backend/                  # Python scripts for preprocessing, training, and evaluation
│   ├── preprocess.py
│   ├── train_model.py
│   └── evaluate.py
├── frontend/                 # Optional simple frontend (could be Streamlit or Flask)
│   └── app.py
├── models/                   # Saved trained models
│   └── spam_classifier.pkl
├── notebooks/                # Jupyter notebooks for exploration and experiments
│   └── EDA_and_Modeling.ipynb
├── data/                     # Dataset folder
│   └── news_dataset.csv
├── README.md                 # Project description
└── requirements.txt          # Python dependencies
