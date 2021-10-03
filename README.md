# A hotel recommender system

I created a hotel recommender system for the full-time Data Science course at [AllWomen](https://www.allwomen.tech). 

**The Dataset**

I found [a great dataset in kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe) from 2017 containing 515K customer reviews of almost 15K luxury hotels from Booking.com I cleaned it and built the recommender system.

**The Business Case**

My main goal was to better understand how travel platforms or apps like Booking.com generate their recommendations.

**The Approach:**
1) Cleaning the dataset
2) Building a Collaborative Filtering Recommender System
3) Using Bayesian Average to calculate the real weight of the ratings
4) Transforming the data into a Matrix and Calculating Sparsity of that Matrix
5) Finding similar hotels using k-Nearest Neighbours
6) Applying Top-N Recommender 

**The Challenges:**

1) The dataset was large and counted with 515K reviews. I needed to gather a smaller sample to be able to manage it but, at the same time, it needed to be big enough so the results were still relevant.
2) The dataset did not provide id for the reviewers so we needed to assign them randomly. In the future it would be interesting to have them beforehand so we could establish patterns between the reviewers and the hotels.

**The Conclusions:**

Genereated a recommender that predicts which hotels a specific user will like depending on their previous ratings. 
