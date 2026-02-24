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
   - By combining both supervised and unsupervised learning in a data set with few labels, one could exploit the data set to a better extent and obtain a better result than just applying each of them individually.

*"If the output of a machine learning model is discrete values, e.g. a boolean value, we then call it a classification model. While we call the model that outputs continuous values a regression model."*

## Classification Model

The input can be represented as a matrix M with dimensions of H×W where <br>
--> H is the height of the photo in pixels <br>
--> W is the width of the photo<br>
Each element within the matrix is the grayscale value of each pixel in the photo, i.e. an integer value between [0,255] that indicates the intensity of colour. The expected output of the model would be a binary value [1∣0], indicating whether the photo shows a cat or not. 
- To summarise, our cat-photo-recognition model F can be formulated as follows:<br>
F(M)∈{0,1},whereM[i][j]∈[0,255],0≤i<H,0≤j<W
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/9af68134-3586-4b9f-b8fd-3a176bc911de" />

## Regression Model


<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/f8c46cc6-f10d-44b8-b34e-1dd7d8b5bd32" />


