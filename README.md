# Sentiment Analysis for Amazon Musical Instrument Reviews

This repository contains code for sentiment analysis on Amazon Musical Instrument reviews. The code preprocesses text data, converts it into word vectors using GloVe embeddings, and builds machine learning models (Logistic Regression and LSTM) to classify sentiment.

## Dataset
The dataset used in this project is available in the file `Musical_instruments_reviews.csv`. It contains reviewer information, review text, ratings, and sentiment labels.

## Preprocessing
The text data undergoes preprocessing steps such as tokenization, removal of stop words, and lemmatization to prepare it for analysis.

## Models Implemented
1. **Logistic Regression Model**
   - Utilizes word vector representations of the text data.
   - Achieves a train accuracy of 99.76% and a test accuracy of 84.30%.

2. **Long Short Term Memory (LSTM) Model**
   - Implements a deep learning model using LSTM layers.
   - Achieves a train accuracy of 88.83% and a test accuracy of 87.29%.

## Additional Features
- **Data Visualization**: Visualizes the distribution of ratings, most common words, sentiment classes, and sequence lengths in the dataset.
- **Cluster Analysis**: Utilizes t-SNE for clustering analysis on word vectors.
- **Handling Imbalanced Dataset**: Implements class weights to handle the class imbalance problem.

## File Structure
- `code.py`: Contains the Python code for sentiment analysis.
- `Musical_instruments_reviews.csv`: Dataset file.
- `README.md`: Instructions and information about the project.

Feel free to explore and utilize this code for sentiment analysis tasks on similar datasets. If you have any questions or suggestions, please don't hesitate to reach out!
