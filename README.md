
# Time Series Forecasting
**Assignment 2** of  the course *Artificial Neural Networks and Deep Learning* at *Politecnico di Milano*: Deep Learning models to to predict future samples of a multivariate time series. The goal is to design and implement forecasting models to learn how to exploit past observations in the input sequence to correctly predict the future.

We were provided with the training dataset, while models were evaluated on a hidden test dataset (not provided). Details about the evaluation procedure are reported [here](https://codalab.lisn.upsaclay.fr/competitions/621#learn_the_details-evaluation)

Project realized with *Keras* module in *Python*.

Details about the dataset and some exploratory data analysis are reported in the first part of the provided Python notebook [notebook_Final](https://github.com/denaldo98/timeseries-forecasting/blob/main/notebook_Final.ipynb).
 
The [notebook](https://github.com/denaldo98/timeseries-forecasting/blob/main/notebook_Final.ipynb) contains also the implementation of the best model we developed to solve the taks, which is a Seq2Seq model with the Attention mechanism.
 
The [report](https://github.com/denaldo98/timeseries-forecasting/blob/main/Challenge2_AN2DL.pdf) *.pdf* file contains the main steps we performed to solve the taks: 

 - Data preparation (data splitting, normalization, building of the supervised samples)
 - Tried models: *hiearchical LSTM*, *LSTM models*, *Seq2Seq* models, *Seq2Seq models with attention*, *Transformer model*
