# Deep Learning Exam Project – Review Classification

**Topic:** Text classification using neural networks  

## Overview
This project was developed as part of my Deep Learning exam. The goal was to process a dataset of park reviews and build a predictive model using deep learning techniques.

## Steps
1. **Data Preprocessing**
   - Loaded and cleaned the `parkReviews.csv` dataset.
   - Removed missing values and standardized review text.
   - Limited review length, applied stopword filtering, and purified text.
   - Used `CountVectorizer` for bag-of-words representation.
   - Encoded categorical features (branch, reviewer location).

2. **Model Design**
   - Built a feed-forward neural network in **Keras** with dense and dropout layers.
   - Applied regularization to prevent overfitting.

3. **Training & Evaluation**
   - Split dataset into training/test sets.
   - Evaluated model performance on text classification task.

## Technologies
- Python, Google Colab  
- Libraries: `pandas`, `scikit-learn`, `keras`  

## Key Learning
The project reinforced knowledge of **text preprocessing, feature engineering, and deep learning model design** for classification tasks.
