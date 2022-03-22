# Twitter-Covid-Vaccination-Data-Sentiment-Analysis

The purpose of this project is to do a sentiment analysis on tweets about covid-19 vaccinations in 3 classes (0-neutral, 1-negative, 2-positive). 
Todo this, i experimented with 4 different types of models:

1. Softmax Regression
2. Feed-Forward neural network.
3. Bidirectional RNN neural network with LSTM & GRU cells (witout and with attention layer).
4. BERT-Base-uncased.


The scores of the best models of each one of theese model types are listed below:

| Model       | Precision   | Recall        | F1 Score | Accuracy | 
| ----------- | ----------- | ------------- | ------ | ------- |
| Softmax Regression | 71 % | 71 %  | 71 % | 71.12 % |
| Feed-Forward neural network   | 58 % |  66 % |  61 % | 65.6 % |
| LSTM neural network | 70 % | 66 % | 67 %  | 65.55 % |
| LSTM with attention layer | 69 % | 72 % | 70 % | 69.36 % |
| BERT-Base-uncased | 78 % | 71 % | 73 % | 71 % |

You can clearly see the increase of the scores when i increase the complexity of the used model (especially in BERT) because the statistical hypothesis in more complex models is usually more accurate.

The code in ipynb notebooks and data used can be found in the corresponding models.

