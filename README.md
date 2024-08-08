# Food_review_rating_Sentiment_Analysis

This project involves creating a sentiment analysis model using a pre-trained BERT model to analyze and score customer reviews from online sources like Yelp. The key steps include:

  1.Installing Dependencies: 
  The project uses Python libraries such as torch, transformers, requests, BeautifulSoup, pandas, and numpy. These are installed to handle deep learning, data processing, and web scraping tasks.

  2.Model Setup:
  The BERT model (nlptown/bert-base-multilingual-uncased-sentiment) is loaded for sentiment analysis. This model is capable of classifying text into sentiment categories ranging from 1 (very negative) to 5 (very positive).

  3.Web Scraping:
  Reviews are scraped from a specific Yelp page using the requests library to fetch the HTML content and BeautifulSoup to parse and extract the reviews.

  4.Sentiment Analysis:
  The extracted reviews are tokenized and passed through the BERT model to predict their sentiment scores.

  5.DataFrame Creation:
  The reviews and their corresponding sentiment scores are stored in a pandas DataFrame, which allows for easy manipulation and analysis of the data.

  6.Sentiment Scoring:
  A custom function is defined to encode the reviews, predict their sentiment using the model, and assign a sentiment score. This score is then added to the DataFrame.

  7.Result Analysis:
  The project ends with the creation of a DataFrame containing the reviews and their respective sentiment scores, providing a clear overview of the sentiment distribution across the reviews.
