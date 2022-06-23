# Tweet-Sentiment-Analysis-Ukraine-war
Big data project to explore the reaction of people on social media towards energy transition before and after Ukraine war, by web scraping tweets that are posted after Russia threatened Europe’s gas supply, along with available data set from Kaggle which contains tweets before the threat (https://www.kaggle.com/datasets/shyambhu/ukraine-war-tweets).

This project is completed using R markdown. 

  - query3.RData contains the web scrapped tweets by using the following query for keywords: 'ukraine' OR '#ukrainewar' AND 'energy'. The data set includes approximately 10.000 tweets that are posted between 12-05-2022 and 18-05-2022.
  - data_before.csv contains pre-processed tweets that are obtained from <https://www.kaggle.com/datasets/shyambhu/ukraine-war-tweets>. 
  
Topic modelling technique, three different lexicons for sentiment analysis at word level, and also sentiment analysis at full tweet level are conducted. 
