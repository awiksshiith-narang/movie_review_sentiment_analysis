# movie_review_sentiment_analysis
This GitHub repository contains the code for performing sentiment analysis on movie reviews. The dataset used for training and evaluation is sourced from Kaggle, ensuring a diverse and comprehensive collection of movie reviews.

The repository includes implementations of various models for sentiment analysis, including:
Plain Embeddings: This model represents the movie reviews as dense vector embeddings and utilizes traditional machine learning algorithms for sentiment classification.
Convolutional Neural Networks (CNNs): This model employs 1D convolutional layers to capture local patterns and extract relevant features from the movie review texts.
Gated Recurrent Units (GRUs): The GRU-based model utilizes recurrent neural networks with gating mechanisms to effectively model the sequential nature of the movie reviews.
Long Short-Term Memory (LSTM) Cells: This model employs LSTM cells, a variant of recurrent neural networks, to capture both short-term and long-term dependencies in the movie review texts.
Stacked Long Short-Term Memory (Stacked LSTM) Cells: This model consists of multiple layers of LSTM cells stacked on top of each other, allowing for more complex representations and enhanced performance.

Among the various models, the best-performing model in this repository is the Convolutional Neural Network (CNN) architecture. CNNs have proven to be highly effective in capturing local patterns and semantic features in text data, making them well-suited for sentiment analysis tasks.
