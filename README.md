# Open-Source-Twitter-Sentiment-Analysis
This project aims to implement sentiment analysis on social network data. While the main model is not built for a competition, the 82% already pretty decent without
hypertuning and ensembling methouds.

Problem Definition:
Processing human languages are actually more complex than we expect. Sarcasm, equivocal, punchline sentence can mean ambiguously to machine. In this data, there are
a lot of key words related to disaster but they are not identified as one. The goal is to predict whether the tweet is actually about a disaster.

Data:
The data can be found: https://www.kaggle.com/c/nlp-getting-started/overview

Ideal Workflow:
1.EDA
2.Preprocessing - tokenize, padding, masking
3.Build model
4.Predict and Submit
