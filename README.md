# Book_Recommendation

**Objective:**

* The main objective of this project is to create a Book recommendation system that best predicts user interests and recommends suitable/appropriate books to them, using various approaches.
* In addition to the ML Model prediction, we also have taken into account the book recommendation for a new user.

**Introduction:**

During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.

In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).

Recommendation systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

Since, here we are trying to recommend books to users based on their past purchases or ratings the user gave previously, we are basically trying different models like Popularity based recommender system, Collaborative filtering based recommender system (user-item or item-item) etc. We will be using the Popularity based recommender system to deal with the cold start problem, where we do not have history of past purchases of a particular user or where the user is totally new.

**Conclusion:**

Findings from EDA::

* The Lovely Bones: A Novel and Wild Animus are the two most read books.
* Stephen King is the most popular book author based on the number of ratings.
* Ballantine Books and Pocket are the top publishers based on the number of ratings that their books have received.
* The majority of readers are between the ages of 25 and 40.
* The majority of readers who have given the books ratings are from the United States and Canada.
* Regardless of the age group, The Lovely Bones and Wild Animus appear on lists of the top-rated books.

Conclusions on Approaches:

* We have built five types of recommendation systems and did evaluation for one of them.
* In the case of Memory-based approach, the Cosine similarity-based KNN performs better at recommending books that are similar than the Euclidean distance-based KNN.
* After evaluation for Collaborative-Model Based Recommendation system, we got a recall@5 of 30% and recall@10 of 41%.
