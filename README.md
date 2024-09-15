This project uses machine learning to classify movie reviews from IMDb as either positive or negative.

Dataset
The dataset contains movie reviews and their sentiment (1 for positive, 0 for negative).

Columns:
review: Text of the movie review.
sentiment: Sentiment label (1 = positive, 0 = negative).
Steps
Data Preprocessing: Clean the text, remove stopwords, tokenize and Lemmatization.
Feature Extraction: Convert text into numerical features using countvectorizer.
Model Training: Train machine learning models like  Random Forest, and Naive Bayes.
Evaluation: Evaluate the models using accuracy, precision, recall, and F1-score.
Requirements
Python 3.x
Libraries: numpy, pandas, scikit-learn, nltk
