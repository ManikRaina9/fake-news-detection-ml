# Fake News Detection using Machine Learning

## Overview
This project demonstrates an end-to-end NLP pipeline including preprocessing, feature engineering, model training, and evaluation.

## Features
- Comprehensive preprocessing: tokenization, stopword removal, lemmatization
- TF-IDF vectorization for feature extraction
- Random Forest classifier for prediction
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix

## Tech Stack
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib, Seaborn  

## Dataset
- Fake.csv: Contains fake news articles  
- True.csv: Contains real news articles  

## Workflow
1. Data integration and labeling  
2. Text cleaning and preprocessing  
3. Feature extraction using TF-IDF  
4. Model training using Random Forest  
5. Performance evaluation  

## Results
Achieved approximately 99% accuracy on the test dataset.

## How to Run

Clone the repository:
```bash
git clone https://github.com/ManikRaina9/fake-news-detection-ml.git
cd fake-news-detection-ml
2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Project:**
    Execute the Python script or Jupyter Notebook:
    ```bash
    python fakenewsdetectionml.ipynb
    ```
