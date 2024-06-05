# Sentiment Analysis of Steam Reviews

## Project Description

This project aims to develop a sentiment analysis system for user reviews on Steam, a popular gaming platform. By leveraging natural language processing (NLP) techniques and machine learning algorithms, the project seeks to automatically classify user reviews into positive, negative, or neutral sentiments. This analysis can help game developers and players gain insights into the general perception of games, identify key areas for improvement, and enhance overall user experience.

## Key Features

- **Data Collection**: Scraping and aggregating user reviews from various games on Steam.
- **Text Preprocessing**: Cleaning and preparing the review texts for analysis.
- **Sentiment Classification**: Using machine learning models to classify the sentiment of each review.
- **Visualization**: Presenting the sentiment distribution and trends through interactive visualizations.

## Technologies Used

- Python
- Natural Language Processing (NLP)
- Machine Learning (e.g., scikit-learn, TensorFlow)
- Data Visualization (e.g., Matplotlib, Seaborn)

## Task Planning

1. Data Collection
    - Extract 3 popular games which are CSGO 2, Helldivers 2 and Need For Speed Unbound.
    - Using [steamreviews@0.9.5](https://pypi.org/project/steamreviews/) package to call the Steam API for reviews.
    - Expected result: reviews in JSON file format
    - Using json and pandas library to convert JSON file to CSV file format
    - Finalized CSV reviews can be acessed [here](https://drive.google.com/drive/folders/1cyj5JmU34nXtflVEVaXNJtIfuJXq6U02?usp=sharing)

2. Text Preprocessing
    - Remove punctuations
    - Converting to lowercases
    - Remove numbers & hyphens
    - Remove certain slang words
    - Do tokenization
    - Remove stopwords
    - Do stemming & lemmatization
  
3. Modeling & Evaluation & Visualization
    - Apply Naive Bayes Confusion Matrix & Classifier Report to observe how does Machine Learning predict the review either positive/negative (supervised learning)
    - Generate Bar Chart for checking number of positive & negative reviews for each particular games
    - Generate Pie Chart to see the percentage of positive & negative reviews for each particular games
    - Generate Boxplot of reviews lengths by sentiment
    - Generate Bar Chart for knowing the average word count by sentiment
    - Generate WordCloud for positive & negative word message (to see the dominant word in the review)
  
4. Sentiment Analysis
    - Based on our project result, we identify those 3 games showed overwhelmingly positive by those players within 1 year period
    - Helldivers 2 stood out the most with a large volume of reviews.
    - The positive response indicates these games are well-received and enjoyed by many players.
    - The analysis benefits both players and developers:
        - Players can make informed decisions about game choices.
        - Developers receive valuable feedback for further game improvement.


Thanks to all my beloved groupmates to make this final project Text Analytic happens <3
1. Aflah SW
2. Afif SW
3. Arinn SW
4. Fauzan IS
