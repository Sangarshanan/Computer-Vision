# Face Recognition using Siamese Neural Network

In order to understand the reason why we have one-shot learning, we need to talk about deep learning and data. Normally, in deep learning, we need a large amount of data and the more we have, the better the results get. However, it will be more convenient to learn only from few data because not all of us are rich in terms of how much data we have.

Also, the brain doesn’t need thousands of pictures of the same object in order to be able to recognize it. But let’s not talk about the brain analogy because it is far more complicated and powerful, and many things are involved in our process of learning and memorization such as feelings, prior knowledge, and interactions, etc.

The idea here is that we need to learn an object class from only a few data and that’s what One-shot learning algorithm is.

## Siamese neural network


Siamese neural network has the objective to find how similar two comparable things are (e.g. signature verification, face recognition..). This network has two identical subnetworks, which both have the same parameters and weights.

![alt text](https://cdn-images-1.medium.com/max/800/1*PIrETF3nqHBQ7K9g9y_p7w.png)


We can apply gradient descent on a triplet loss function which is simply a loss function using three images: an anchor image A, a positive image P(same person as the anchor), as well as a negative image N (different person than the anchor). So, we want the distance d(A, P) between the encoding of the anchor and the encoding of the positive example to be less than or equal to the distance d(A, N) between the encoding of the anchor and the encoding of the negative example. In other words, we want pictures of the same person to be close to each other, and pictures of different persons to be far from each other.





### Reference: 

https://towardsdatascience.com/one-shot-learning-face-recognition-using-siamese-neural-network-a13dcf739e

https://www.coursera.org/learn/convolutional-neural-networks/home/welcome

