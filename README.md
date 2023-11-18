# attention-lstm-quantitative-trading

trying to recreate an ArXiv paper: 
Using LSTM in Stock prediction and Quantitative
Trading
Zhichao Zou
Center for Professional Development
Stanford University
SUNetID: zzou
zzou@stanford.edu
Zihao Qu
Center for Professional Development
Stanford University
SUNetID: quzihao
quzihao@stanford.edu

## Findings:
The LSTM model did not achieve the same level of performance (negative or zero returns, no alpha versus significantly above-average returns) using the same strategy. It is possible that the use of different hyperparameters and variations in data contributed to the model's reduced effectiveness. Additionally, I was unable to find a reliable source for the stock's beta, and data quality may have been a concern. The data I gathered, collected using APIs and web scraping, may have been compromised due to potential errors in the data collection process, which can significantly impact results. However, it might also be the case that deep learning has not yet sufficiently advanced for application in finance; JP Morgan recently ceased using deep learning for FX algorithms, citing its unexplainability: [JP Morgan Article Link](https://www.risk.net/derivatives/7958022/jp-morgan-pulls-plug-on-deep-learning-model-for-fx-algos). My hypothesis is that if JP Morgan had developed a black box that made consistently sound decisions, their clients would likely not have questioned its methods, and the firm would have continued its use. This does not imply that deep learning cannot be employed in finance at all, but rather that the specific approach I utilized was flawed. For instance, focusing on price as the dependent variable, or even on price changes, might be incorrect. Daily data might not be granular enough for pattern discovery. Additionally, a significant amount of public data was not collected in my approach, not to mention alternative data available to many firms and insider information. Perhaps a model with more features and better feature engineering might eventually identify patterns in stock prices that could be leveraged to achieve above-average returns. However, it is evident that this is not a straightforward task.
