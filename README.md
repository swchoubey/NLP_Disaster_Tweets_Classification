Twitter is one of the most consistently popular social networking platform. Twitter users can follow
relevant hashtags, search for people, topics, and keywords, or even subscribe to a list to learn more
information about a specific topic. According to an article, 206 million users access Twitter daily.
With the use of Natural Language Processing, we can identify if a tweet is about a real disaster and
take immediate action. This was the main goal of this project, predict whether a tweet is about a real
disaster or not. I used the dataset provided on Kaggle consisting of a training set of 10,000 hand
classified tweets. For the purpose of identifying if a tweet is pertaining to a disaster or not, I tried out
a variety of different models which have been itemized below:

1. Logistic Regression
2. Gaussian Naive Bayes
3. Linear Kernel SVM
4. RBF Kernel SVM
5. Random Forest

#Performance Analysis

![image](https://user-images.githubusercontent.com/97143500/165002188-c5743d05-caa9-4d51-b131-89448490b8af.png)

As far as accuracy and precision are concerned, SVM models are the best with RBF Kernel SVM
being at the top with an accuracy of 0.8. Logistic Regeression also performed well. 

#Analysis of Accuracy

![image](https://user-images.githubusercontent.com/97143500/165002232-54719879-3858-4ed3-99c1-d09343120a5c.png)

#Analysis of Time taken by each Algorithm

![image](https://user-images.githubusercontent.com/97143500/165002272-3daeb672-b188-4fd7-8b9a-cc9cf917e1c3.png)

