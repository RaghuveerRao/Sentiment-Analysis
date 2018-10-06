# Sentiment-Analysis
Sentiment Analysis of "management discussion and analysis" to identify management sentiment

This is a simple example of basic sentiment analysis done on "Management discussion & analysis" report available in 10K annual filings of a firm. The goal is to evaluate the sentiment of the management and identify any trends over the years. 

The firm picked here is Dollar General. Past 5 years of Dollar General's "Management, Discussion and Analysis" is available in the data folder. 


### The LoughranMcDonald Master Dictionary
The dictionary provides a means of determining which tokens (collections of characters) are actual words, which is important for consistency in word counts. along with the sentiment for each word (positive or negative). The reason for using the dictionary is that generic dictionaries misclassify common words in a financial text. In a large sample of 10 Ks from 1994 to 2008, almost three-fourths of the words identified as negative by the widely used Harvard Dictionary are words typically not considered negative in financial contexts.
For example, the word liability would be considered a negative in general context. But its a valid common word in financial reports.

Further reading: https://www3.nd.edu/~mcdonald/Word_Lists_files/Documentation/Documentation_LoughranMcDonald_MasterDictionary.pdf
