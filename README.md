# Machine-Translation-seq2seq-with-attention

Using seq2seq machine translation from English to French.
Attention has been included to show the weights of each English word corresponding to the prediction of each German words
![Image of ba](https://github.com/ccw0530/Machine-Translation-seq2seq-with-attention/blob/master/ba.jpeg)
Also, teacher forcing is used during training by feeding the correct words if the model has predicted next words wrongly to ensure the model wont predict completely wrongly if the previous words are wrong. It may increase the learning efficiency.

![Image of t1](https://github.com/ccw0530/Machine-Translation-seq2seq-with-attention/blob/master/sent1.png)
![Image of gt1](https://github.com/ccw0530/Machine-Translation-seq2seq-with-attention/blob/master/gt1.png)

![Image of t2](https://github.com/ccw0530/Machine-Translation-seq2seq-with-attention/blob/master/sent2.png)
![Image of gt2](https://github.com/ccw0530/Machine-Translation-seq2seq-with-attention/blob/master/gt2.png)
