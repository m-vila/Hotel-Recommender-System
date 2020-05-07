# A hotel recommender system

As my final project for the full-time Data Science course at [AllWomen](https://www.allwomen.tech) I created a hotel recommender system.

My main goals were:
1) To better understand how travel platforms like Booking.com generate their recommendations
2) To find the best hotels to plan my next trip

I found [a great dataset in kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe) from 2017 containing 515K customer reviews of almost 15K luxury hotels (3 to 5 stars) from Booking.com.

In this repository there are six files:

0. Scrapping Booking.com - notebook to perform a web scraping from Booking.com of the 15K hotels to get the updated information for 2020
1. Loading, Cleaning and EDA of the 2017 data - notebook exploring the data from the kaggle competition
2. Loading, Cleaning and EDA 2020 dataset - notebook exploring the newly extracted data
3. Sentiment Analysis of the 2017 data - notebook where I carry sentiment analysis
4. Topic Modelling of the 2017 data - notebook where I perform topic modelling analysis
5. Recommender System 2017 data - notebook where I build the hotel recommender system
