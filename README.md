# StockPrediction

# 1. For Yahoo Finance using Reinforcement Learning
Stock Prediction by Reinforcement Learning.

It's implementation of Q-learning applied to (short-term) stock trading. 
The model uses n-day windows of closing prices to determine if the best action to take at a given time is to buy, sell or sit.

As a result of the short-term state representation, the model is not very good at making decisions over long-term trends, but is quite good at predicting peaks and troughs
## Usage

- To train the model :   
```
cd ReinforcementLearning-YahooFinance
mkdir models
python train.py ^GSPC 10 1000`
```
- Then after training finishes : 
```
python evaluate.py ^GSPC_2011 model_ep1000
```
## Tutorial 
Jupyter Notebook for stock prediction.

## References 
[Deep Q-Learning with Keras and Gym](https://keon.io/deep-q-learning/) - Q-learning overview and Agent skeleton code

[Siraj Raval-School of AI](https://www.theschool.ai/courses/move-37-course/)


# 2. Google Stock Prediction Using Recurrent Neural Network

- Google Stock Prediction Using Recurrent Neural Network
- see plot in RNN-GoogleStock
