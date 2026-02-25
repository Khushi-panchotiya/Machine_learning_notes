### What is a Machine Learning algorithm and a Machine Learning Model?
Ans: A machine learning algorithm is the process that uncovers the underlying relationship within the data. <br>
The outcome of a machine learning algorithm is called a machine learning model, which can be considered as a function F that outputs certain results when given the input.

- The task of machine learning is to learn the function from the vast mapping space.

## Supervised Learning

--> In a supervised learning task, the data sample would contain a target attribute y, also known as **ground truth**.<br>
And the task is to learn a function F that takes the non-target attributes X and outputs a value that approximates the target attribute, i.e. F(X)≈y. <br>

- The data with the target attribute is called **"labelled"** data.
- Used most in real-world applications.

<table>
   <thead>Examples</thead>
   <th> Input (X) </th> 
   <th> Output (Y) </th>
   <th> Application </th>
   <tr>
      <td>email</td>
      <td>Spam?(0/1)</td>
      <td>Spam filtering</td>
   </tr>
   <tr>
      <td>audio</td>
      <td>text transcripts</td>
      <td>Speech recognition</td>
   </tr>
   <tr>
      <td>Language_1</td>
      <td>Language_2</td>
      <td>Machine translation</td>
   </tr>
   <tr>
      <td>ad, user info</td>
      <td>click? (0,1)</td>
      <td>Online advertising</td>
   </tr>
   <tr>
      <td>image, radar info</td>
      <td>position of other cars</td>
      <td>Self driving car</td>
   </tr>
   <tr>
      <td>image of phone</td>
      <td>defect? (0,1)</td>
      <td>Visual inspection</td>
   </tr>
</table>

## Unsupervised Learning

--> We don't have ground truth in an unsupervised learning task.<br>
--> We try to find patterns or Structures in the data.<br>
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
- classification predicts categories.
- Small finite number of possible outputs.
- 
The input can be represented as a matrix M with dimensions of H×W where <br>
--> H is the height of the photo in pixels <br>
--> W is the width of the photo<br>

Each element within the matrix is the grayscale value of each pixel in the photo, i.e. an integer value between [0,255] that indicates the intensity of colour. The expected output of the model would be a binary value [1∣0], indicating whether the photo shows a cat or not. 
- To summarise, our cat-photo-recognition model F can be formulated as follows:<br>
F(M)∈{0,1},whereM[i][j]∈[0,255],0≤i<H,0≤j<W
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/9af68134-3586-4b9f-b8fd-3a176bc911de" />

## Regression Model

- Predicting a number from infinitely many possible outputs.
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/f8c46cc6-f10d-44b8-b34e-1dd7d8b5bd32" />


