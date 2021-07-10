# Sentiment-Classification

* Dataset : [https://www.kaggle.com/c/tweet-sentiment-extraction/data](https://www.kaggle.com/c/tweet-sentiment-extraction/data)

Models used : 
* LSTM
* LSTM with pretrained Glove Embedding (300d)
* CNN with pretrained Glove Embedding with 1D convolution.

Results : 

| Model        | Val-accuracy | Test-accuracy |
|--------------|--------------|---------------|
| LSTM         | 70%          | 71%           |
| LSTM + Glove | 74.2         | 74.49         |
| CNN + Glove  | 72.4         | 71.84         |

