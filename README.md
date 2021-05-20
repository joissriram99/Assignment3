# Assignment3
The random data is generated using torch.randint of shape (batch-size,1).

The random input is concatenated with the flattened layer from the model.

I have used Adam optimizer,Adam combines the finest features of the AdaGrad and RMSProp methods to create an optimization technique for noisy issues with sparse gradients. Adam is simple to set up, and the default configuration parameters work well for the majority of problems.

To evaluate the results I considered Cross Entropy Loss, because this is a classification problem.Maximizing the likelihood of a multinomial distribution with cross-entropy and softmax is equivalent to maximizing the likelihood of a multinomial distribution. Because the decision boundary in a classification task is large, cross-entropy (or softmax loss, but cross-entropy works better) is a better measure than MSE for classification.
