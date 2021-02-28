# Recommendation_Amazon_Electonics

Problem Statement:

   Online E-commerce websites like Amazon, Filpkart uses different recommendation models to provide different suggestions to different users. Amazon currently uses item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real time. This type of filtering matches each of the user's purchased and rated items to similar items, then combines those similar items into a recommendation list for the user.
   
  In this project I am going to build recommendation model for the electronics products of Amazon. The electronics dataset here is taken from http://jmcauley.ucsd.edu/data/amazon/

Dataset columns - first three columns are userId, productId, and ratings and the fourth column is timestamp. 
Analysis is done based on the below steps:

    1)  Read and explore the given dataset
    2)  Take a subset of the dataset to make it less sparse/ denser. ( For example, keep the users only who has given 50 or more number of ratings )
    3)  Split the data randomly into train and test dataset. ( For example, split it in 70/30 or 75/25 )
    4)  Build Popularity Recommender model
    5)  Build Collaborative Filtering model
    6)  Evaluate both the models 
    7)  Get top - K ( K = 5) recommendations. Since our goal is to recommend new products to each user based on his/her habits, we will recommend first 5 new products
    8)  Summarize the insights

