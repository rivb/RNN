# RNN

Recurrent Neural Networks are a type of arquitecture in which neurons have a short term memory with respect of what it have happen before, so it save the result of the first neurons by using its output as input for the next neurons, so in this way it can analyse it with respect what have happen in the past.

One of the problem of RNN is that it's memory is too short, so neurons that are in first place are not taken in account by the neurons that are in the end, that is why is said that they have short term memory. Also, other problem that occur is that training the network all the way back to the first neurons will lead to vanishing gradient descent issue.

For that reason, Long Short Term Memory (LSTM) came to the rescue.

#LSTM
