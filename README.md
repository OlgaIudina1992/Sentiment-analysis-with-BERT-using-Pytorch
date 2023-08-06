# Sentiment-analysis-with-BERT-using-Pytorch
Sentiment analysis project using a BERT model from Hugging Face in Pytorch, with BeautifulSoup for web scraping

# The aim of the project: 
Analyze customer sentiment towards Lush products using Trustpilot reviews

# Stages:
1. Collecting data from Trustpilot using BeautifulSoup and adding them to a dataframe (total reviews collected: 2227)
2. Using HuggingFace's pre-trained BERT to analyze sentiment (https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment)
3. Visualizing results with pyplot

# Results:
An overwhelming majority of the reviews - 64% - are negative, with extremely positive (5) reviews in the second place - 21%. All the other percentages are negligible.

# Improvements:
Review dates, if scraped, can illustrate the change in customer sentiment over time and serve as basis for further analysis.
