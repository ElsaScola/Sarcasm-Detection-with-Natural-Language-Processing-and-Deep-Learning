# Sarcasm Detection with Natural Language Processing and Deep Learning

This repository contains the code of the study "Sarcasm Detection with Natural Language Processing and Deep Learning".
The following files/folders can be found:

- **data**: contains the train, test and validation partitions used for the study. The original data comes from [News Headlines Dataset For Sarcasm Detection](https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection), which contains two files that were merged and cleaned by dropping duplicates and initializing a new index. Finally the partitions were created by using 70% of the data for training (19,952 instances), 20% for testing (5,700 instances) and 10% for validation (2,850 instances). 
- **LSTM.ipynb**: contains the implementation of the LSTM approach for sarcasm detection.
- **lstm_FN.csv** and **lstm_FP.csv**: contain the False Negatives and False Positives of the results by the LSTM model, which are used for posterior analysis. 
- **BERT.ipynb**: contains the implementation of the BERT approach for sarcasm detection.
- **bert_FN.csv** and **bert_FP.csv**: contain the False Negatives and False Positives of the results by the BERT model, which are used for posterior analysis. 


