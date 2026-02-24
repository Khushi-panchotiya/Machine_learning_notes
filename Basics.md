### What is a Machine Learning algorithm and a Machine Learning Model?
Ans: A machine learning algorithm is the process that uncovers the underlying relationship within the data. <br>
The outcome of a machine learning algorithm is called a machine learning model, which can be considered as a function F that outputs certain results when given the input.

- The task of machine learning is to learn the function from the vast mapping space.

## Supervised Learning

--> In a supervised learning task, the data sample would contain a target attribute y, also known as **ground truth**.<br>
And the task is to learn a function F that takes the non-target attributes X and outputs a value that approximates the target attribute, i.e. F(X)≈y. <br>

- The data with the target attribute is called **"labelled"** data.

## Unsupervised Learning

--> We don't have ground truth in an unsupervised learning task.<br>
One is expected to learn the underlying patterns or rules from the data, without having the predefined ground truth as the benchmark.

### Example of Unsupervised learning tasks:

1. Clustering
   - Given a data set, one can cluster the samples into groups based on the similarities among the samples within the data set.
2. Association
   - Given a data set, the association task is to uncover the hidden association patterns among the attributes of a sample.
3. Semi-supervised Learning
   - In a scenario where the data set is massive but the labeled sample are few, one might find the application of both supervised and unsupervised learning. We can call this task semi-supervised learning.
   - By combining both the supervised and unsupervised learning in a data set with few labels, one could exploit the data set to a better extent and obtain a better result than just applying each of them individually.
   
