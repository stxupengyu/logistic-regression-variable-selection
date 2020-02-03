# logistic-regression-variable-selection
Use logistic regression to predict default events. We first discretize the continuous variables, then encode them with one hot code. Finally, we use RFE in the sklearn library to select the variables and get 11 significant features. Finally, the precision, recall and F1 score of 0.75 + are obtained on the test set.  
****
![Image text](https://github.com/stxupengyu/logistic-regression-variable-selection/blob/master/img-folder/1.png)  
![Image text](https://github.com/stxupengyu/logistic-regression-variable-selection/blob/master/img-folder/2.png)  
****
使用logistic回归预测违约事件。我们首先对连续性变量进行离散化，之后进行one-hot编码，最后利用sklearn库中的RFE进行变量选择，得到结果显著的11个特征。最后在测试集上获得了0.75+的precision,recall and F1-score.  
