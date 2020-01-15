# RNN

Recurrent Neural Networks are a type of arquitecture in which neurons have a short term memory with respect of what it have happen before, so it save the result of the neurons before by using its output as input for the next neurons, so in this way it can analyse the output with respect what have happen in the past.

One of the problem of RNN is that it's memory is too short, this is because the short memory only consider what have happen before but not what happen before that. Also, other problem that occure is that training the network all the way back to the first neurons will lead to vanishing gradient descent issue.

For that reason, Long Short Term Memory (LSTM) came to the rescue.

![alt text](https://raw.githubusercontent.com/rvaldivia95/RNN/branch/path/to/rnn.png)

# LSTM

Long Short Term Memory architecture have two type of memory, one that consider Long Term Memory (LTM) and Short Term Memory( STM). It recieve this both type of memory including the New Input that must to classified and they are process by 4 different gates, forget gates, learn gate, remember gate and use gate. Forget gate recieve the information of LSTM AND Learn gate recieve the information of the New Input and the STM. Then the remmember gate decide what would be the next LSTM, that is the combination of the forget gates and learn gate. Next the use gate combine forget gates and learn gate to decide what would be the output, that in this case would be the STM.
