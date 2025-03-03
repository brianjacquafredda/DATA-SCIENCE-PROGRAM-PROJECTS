# DATA-SCIENCE-PROGRAM-PROJECTS
This Repository shows all the Data Science Projects that I worked on in the Master of Science in Data Science and Analytics at Elmhurst University in Elmhurst, IL.

I wanted to publish my favorite and most successful Data Science Project I completed in the Data Science Program. I used Text Analytic methods, such as News Sentiment Scores using publically available data from the Federal Reserve of San Francisco (Source #1) and Daily CNBC 5 Things to Know Before the Stock Market Opens Articles (Source #2) using NTLK Vader Lexicon Scores.

Source #1 : https://www.frbsf.org/research-and-insights/data-and-indicators/daily-news-sentiment-index/
Dataset used: 

Source #2: https://www.cnbc.com/2023/02/27/5-things-to-know-before-the-stock-market-opens-dayoffweek-month-monthdaynum
Example:
### 02/27/2023
### url = 'https://www.cnbc.com/2023/02/27/5-things-to-know-before-the-stock-market-opens-monday-february-27.html'

Contents:

1. DailySentimentScores_CNBC.ipynb.ipynb <- This takes the 'Premarket_Newsfeeds_v2.csv' and gives it a Text Sentiment Score on the CNBC Articles...
2. MachineLearningResultsDowJonesPredict <- train_text_v2 dataset - the Data on Previous News Sentiment Scores from Federal Reserve and the Historical Dow Jones Results on Closing on a Daily Basis.
3.  MachineLearningResultsDowJonesPredict <- test_text_v2 dataset is the Sentiment Scores from the CNBC articles with the results of the previous session of the Dow Jones Closing Results.

The results were surprising, as I had a 73.33% Accuracy Rating of Predicting the Dow Jones on a Daily Basis. I would not take it as Financial Advice my professor noted.

# Prediction ### 0,0,0,1,1,1,1,0,0,0,0,0,1,1,1
# Actual     ### 0,0,1,1,1,1,0,0,0,0,0,1,1,1,0
# Results    ### 1,1,0,1,1,1,0,1,1,1,1,0,1,1,0

11/15
0.73333333333
   
