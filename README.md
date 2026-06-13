Project Title: Fake News Detection using NLP & Logistic Regression
Description:
Built an AI-powered fake news detection system using Natural Language Processing and Logistic Regression. The model was trained on 44,898 labelled news articles and achieved 98.6% accuracy on unseen test data — correctly classifying 8,853 out of 8,980 articles.

Technologies Used:
Python 3
Pandas, NumPy
Scikit-learn (TfidfVectorizer, LogisticRegression)
Matplotlib

Dataset:
Fake.csv (fake articles — label 0) and True.csv (real articles — label 1)
Combined, shuffled, and split 80% training / 20% testing

How it works:
Combined article title + body text for richer features
TF-IDF Vectorizer converts text into a 130,000+ column numerical matrix
Logistic Regression classifier predicts Real (1) or Fake (0)
Evaluated using confusion matrix, precision, recall and F1 score
