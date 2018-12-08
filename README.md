# StockPrediction
Stock Prediction by Reinforcement Learning.

It's implementation of Q-learning applied to (short-term) stock trading. 
The model uses n-day windows of closing prices to determine if the best action to take at a given time is to buy, sell or sit.

As a result of the short-term state representation, the model is not very good at making decisions over long-term trends, but is quite good at predicting peaks and troughs
## Usage

- To train the model :   
```
mkdir models
python train.py ^GSPC 10 1000`
```
- Then after training finishes : 
```
python evaluate.py ^GSPC_2011 model_ep1000
```
