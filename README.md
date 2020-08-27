# simple_java_deeplearning
2017 1st semester last java assignment
Let’s classify the performance of each three DNNs. We can evaluate the performance of a model via Accuracy, Precision, Recall and F1 Score.<br>
Accuracy is the most intuitive performance measure and it is simply a ratio of correctly predicted observation to the total observations. If we have high accuracy then its model is good. Accuracy is a great measure but only when you have symmetric datasets where values of false positive and false negatives are almost same. Therefore, parameters are need to evaluate the performance of these models. <br>
Precision is the ratio of correctly predicted positive observations to the total predicted positive observations. High precision relates to the low false positive rate. <br>
Recall is the ratio of correctly predicted positive observations to the all observations in actual class. <br>
F1 Score is the weighted average of Precision and Recall. Therefore, this score takes both false positives and false negatives into account. Intuitively it is not as easy to understand as accuracy, but F1 is usually more useful than accuracy, especially if you have an uneven class distribution. <br>
So, if the accuracy, precision, recall and f1 score are high, it has a good performance. Among the results of three DNNs, second has the highest performance. And then, performance is high in the first and third order. <br>
First result only use three layers and use ReLU function. ReLU is the activation function which has no saturation problem at all. So it is computationally efficient. <br>
Second result use four layers and use ReLU function. And its performance is better than first one. So, the more layers there are, the better the performance will be. <br>
Third result use four layers and use ELU function. Its number of layers are same as second one, but the result of both are different. So, in some case, ReLU function will be better than ELU to improve the model’s performance.
