# Assignments overview

## W01

### Lab 01: K-Means
In this practice lab, we implemented the k-means clustering algorithm and use it for image compression.

<img src="https://github.com/coderleonardo/Machine_Learning_Specialization-Coursera/blob/main/C03-Unsupervised_Learning_Recommenders_and_Reinforcement_Learning/W01/Lab01/images/figure%203.png" alt="K-Means for compression" style="height: 250px; width:700px;"/>

### Lab 02: Anomaly Detection
In this practice lab, we implemented the anomaly detection algorithm and apply it to monitor computer servers to identify potentially failing (anomalous) servers.

<img src="https://github.com/coderleonardo/Machine_Learning_Specialization-Coursera/blob/main/C03-Unsupervised_Learning_Recommenders_and_Reinforcement_Learning/W01/Lab02/images/figure3.png" alt="Anomaly Detection" style="height: 500px; width:500px;"/>

## W02

### Collaborative Filtering

#### Some Questions
Collaborative filtering system will be the most appropriate learning algorithm, for example, if you run an online bookstore and collect the ratings of many users. You want to use this to identify what books are "similar" to each other (i.e., if a user likes a certain book, what are other books that they might also like?)

Also, for recommender systems with binary labels y, these are reasonable ways for defining when y should be 1 for a given user j and item i:

		- y is 1 if user j fav/likes/clicks on item i (after being shown the item).
			(fav/likes/clicks on an item shows a user's interest in that item. It also shows that an item is interesting to a user.)
		- y is 1 if user j purchases item i (after being shown the item).
			(Purchasing an item shows a user's preference for that item. It also shows that an item is preferred by a user.)
			
#### Lab01
In this lab, we build a collaborative filtering recommender system for recommending movies using Tensorflow.
