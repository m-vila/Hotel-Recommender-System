# A hotel recommender system

This is a project for the full-time Data Science course at [AllWomen](https://www.allwomen.tech) where I created a hotel recommender system.

**The Dataset**

I found [a great dataset in kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe) from 2017 containing 515K customer reviews of almost 15K luxury hotels from Booking.com and built the recommender system from that new dataset.

**The Business Case**

My main goals were:
1) To better understand how travel platforms like Booking.com generate their recommendations
2) To find the best hotels to plan my next trip in 2020 (little did I know that the pandemic had other plans for me)

**The Approach:**
1) Cleaning the dataset
2) Building a Collaborative Filtering Recommender System
3) Using Bayesian Average¶for the ratings
4) Transforming the Data into a Matrix and Calculating Sparsity of the Matrix
5) Finding similar hotels using k-Nearest Neighbours
6) Top-N Recommender¶

**The Challenges:**
1) The dataset is large and counts with 515K reviews. I needed to gather a smaller sample to be able to manage it better but big enough so the results were still relevant.
2) The dataset did not provide id for the reviewers so we needed to assign them randomly. In the future it would be interesting to have them so we could establish patterns between the reviewers and the hotels.

**The Conclusions:**
