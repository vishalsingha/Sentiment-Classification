# Sentiment-Classification

* Dataset : [https://www.kaggle.com/c/tweet-sentiment-extraction/data](https://www.kaggle.com/c/tweet-sentiment-extraction/data)

Models used : 
* LSTM
<img src = "https://github.com/vishalsingha/Sentiment-Classification/blob/main/Images/lstm.png?raw=true" heaight="200px" width="200px">
<img src = "https://github.com/vishalsingha/Sentiment-Classification/blob/main/Images/lstm_glove.png?raw=true" heaight="200px" width="200px">
<img src = "https://github.com/vishalsingha/Sentiment-Classification/blob/main/Images/CNN.png?raw=true" heaight="200px" width="200px">

* LSTM with pretrained Glove Embedding
* CNN with pretrained Glove Embedding

Results : 

| Model        | Val-accuracy | Test-accuracy |
|--------------|--------------|---------------|
| LSTM         | 70%          | 71%           |
| LSTM + Glove | 74.2         | 74.49         |
| CNN + Glove  | 72.4         | 71.84         |

