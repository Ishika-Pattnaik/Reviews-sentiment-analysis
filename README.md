# Reviews-sentiment-analysis
Sentiment Analysis – Task 2
In this task, I built a sentiment analysis system using two approaches:
1. Baseline Model – TF-IDF + Logistic Regression
Preprocessed the Amazon reviews dataset using TF-IDF vectorization.
Trained a Logistic Regression classifier as a simple baseline.
Evaluated performance using accuracy, precision, recall, and F1-score.
2. LSTM Model with GloVe Embeddings
Built a deep learning model using an LSTM network.
Used pre-trained GloVe word embeddings to optimize text representation.
Set up training with early stopping and learning rate reduction for efficiency.
Saved the model after partial training (16 epochs).
3. Also tried training the transformer distilBERT from HuggingFace which is provided in a different notebook.

   
⚠️ Due to time constraints and limited GPU availability, I couldn’t fully train the LSTM model to convergence.
However, I saved the intermediate results and metrics to compare with the baseline.

👉 Final step: Compared the baseline vs. LSTM model performance using accuracy, precision, recall, and F1-score.
