# Sentiment-Analysis-and-Recommendation
Final Year Project done from September 2021 to June 2022

**Project Summary:**

The project focuses on sentiment analysis of Amazon book reviews to provide personalized book recommendations to users. Since the data we scraped was not enough, we have used GoodReads data for sentiment analysis and recommendation. By analyzing customer reviews, the system aims to understand the sentiment behind the reviews and recommend books that align with the user's preferences.  Here's how the recommendation process works:

**Data Preparation:** Customer reviews from GoodReads, along with metadata about the books, are collected and preprocessed. The data is cleaned to remove irrelevant information and prepared for analysis.
**Sentiment Analysis:** Sentiment analysis is performed on the reviews using machine learning (Logistic Regression, Random Forest) and deep learning (LSTM, CNN) algorithms. This analysis helps determine the overall sentiment (positive, negative, neutral) of each review.
**Feature Extraction:** Features such as TF-IDF (Term Frequency-Inverse Document Frequency) and word embeddings (GloVe, Word2Vec) are extracted from the preprocessed text data. These features capture the essential information required for sentiment analysis.
**Book Recommendation:** Once the sentiment scores for each book are calculated, collaborative filtering is applied. The system computes pairwise correlations between books based on their sentiment scores and other metadata. When a user expresses interest in a particular book or genre, the system recommends other books.

**Tools/Packages Used:**
1. Python 3
2. Anaconda Distribution
3. Beautiful Soup
4. Scrapy Framework
5. NLTK (Natural Language Toolkit)
6. Scikit-learn
7. Gensim
8. TensorFlow/Keras
9. Pandas
10. NumPy

The project leverages various Python libraries and frameworks for data scraping, preprocessing, machine learning, deep learning and data analysis tasks.
