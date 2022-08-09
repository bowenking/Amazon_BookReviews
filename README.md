# Amazon_BookReviews: Using Amazon Kindle Reviews to identify books for potential exclusive copyrights purchases
 
The dataset came from Kaggles.com: https://www.kaggle.com/datasets/bharadwaj6/kindle-reviews

The data is collected from customers’ product reviews from the Amazon Kindle Store platform. It ranges from May 1996 to July 2014 and carries a total of 982,619 data entries. Every reviewer and product in the dataset has a minimum of 5 reviews

In this project, topic modeling is leveraged to generate the genre labels from sampled reviews on Amazon eBook platform. 
The result of unsupervised modeling is used as the target for training the SVM classification model. The trained model is then used to predict the unlabeled reviews. 
For each topic bucket, the top 10 books with the highest average overall rating is recommended. Sentiment analysis is used to confirm the performance of selected books.