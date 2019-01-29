# NLP - Text Summarization and Document Classification
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

This is a project work of Xccelerate Data Science Bootcamp Cohort 3.

## Project work for Natural Language Processing:

1. Find a document and auto-summarize it. It can be a blog/news article/research paper. Use a machine based approach for this. 

    2 versions of text summarization are built:
    * Version 1: Do word count of the paragraph. The score of each word will be its occurrence.
    * Version 2: Using TF-IDF for summarization.

    Due to time-constraint, the machine learning part is still to be developed. You can go to the [notebook](https://github.com/youonf/text_summarization_document_classification/blob/master/notebook) to find out more.

    **Skills**: BeautifulSoup, nltk, TF-IDF (without using tfidf vectorizer)


2. Find a list of blogs from any website and find a theme. Use this learning to test if new articles can have be classified into themes as well.

    2 models are built:
    * Version 1: K-means to classify TF-IDF matrix of the news articles
    * Version 2: Supervised learning for news articles categorization

    **Skills**: nltk, K-means, elbow method, Silhouette Coefficient, tfidf_vectorizer, randomforestclassifier, xgboost, LinearSVC, KNN