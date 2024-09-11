
# COVID-19 Tweet Sentiment Analysis and Topic Modeling

## Project Introduction

The COVID-19 pandemic has significantly impacted public discourse, with social media platforms like Twitter becoming a primary outlet for individuals to express their thoughts, opinions, and emotions. Analyzing this vast amount of text data can provide valuable insights into public sentiment and perceptions surrounding the pandemic. This project aims to perform sentiment analysis on a dataset of tweets related to COVID-19. The tweets have been manually tagged with sentiment labels, which will serve as the target for classification. The sentiment classification task involves preprocessing the tweet data, extracting features, and applying machine learning models to predict sentiment categories.

## Project Objectives

1. **Data Preprocessing**: 
   - Clean the raw tweet data by removing unnecessary punctuations, stopwords, and any words with a length of 1 or 2 characters. This ensures the dataset is free from noise and irrelevant words, improving the accuracy of the model.

2. **Visualizing Data**:
   - Generate a word cloud to visualize the most frequent words in the cleaned dataset. This will help understand the dominant terms being discussed in the tweets related to COVID-19.

3. **Topic Modeling with LDA**:
   - Apply the Gensim LDA (Latent Dirichlet Allocation) model to extract topics from the tweet corpus. The number of topics will be set to 20, and a visualization will be created to explore the underlying themes in the data. Additionally, an analysis will be performed to determine how many topics are ideal for this dataset.

4. **Sentiment Classification**:
   - Use the TF-IDF (Term Frequency-Inverse Document Frequency) feature extraction technique along with a Random Forest Classifier to build a model that predicts the sentiment of tweets. This is a multiclass classification problem, and relevant hyperparameters for the classifier will be tuned to optimize performance. The model's precision and recall metrics will be calculated to evaluate its effectiveness.

By achieving these objectives, this project will develop a robust sentiment classification model and explore the thematic structure of COVID-19-related tweets, providing insights into public sentiment during the pandemic.
