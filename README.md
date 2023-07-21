# Anime_Recommendation
This is a machine learning project that aims to build an Anime Recommendation System using the Cosine Similarity Model. The system will analyze user preferences and provide personalized anime recommendations based on similarities between users and anime items in the dataset.

# Dataset
The dataset used for this project is sourced from Kaggle and is provided by Cooper Union. It is called the "Anime Recommendations Database" and can be accessed via the following link: Anime Recommendations Database.

The dataset consists of two main files:

* anime.csv: Contains information about various anime, including their names, genres, and types.
* rating.csv: Contains user ratings for different anime items.

# Cosine Similarity Model
The recommendation system uses the Cosine Similarity Model to calculate similarities between users and anime items. Cosine Similarity is a measure of similarity between two non-zero vectors and is commonly used in collaborative filtering-based recommendation systems.

## The steps involved in building the recommendation system are as follows:

1. Load the dataset and perform necessary data preprocessing.
2. Create a user-item matrix with ratings, where rows represent users, columns represent anime items, and the values are user ratings.
3. Calculate the Cosine Similarity between users or items, depending on the recommendation approach.
4. Identify the top similar users or items based on the calculated similarity scores.
5. Generate personalized anime recommendations for each user by considering the anime items preferred by similar users or items.

# Results
The performance and accuracy of the recommendation system may vary based on the dataset size, user preferences, and the quality of ratings. The system aims to provide relevant anime recommendations tailored to individual users.
