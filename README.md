# Rank Scoring via Collaborative Filtering
Efficient implementation of User-User and Item-Item Collaborative Filtering in Python using parallelization for faster pre-processing.

## Collaborative Filtering
Collaborative Filtering is a scoring algorithm based on prior knowledge used in recommendation systems.

**User-User** collaborative filtering ranks and scores possible recommendations by assessing whether or not users similar to the subject have a history of liking the item in question.

**Item-Item** collaborative filtering ranks and scores possible recommendations by assessing whether or not the subject have a history of liking things similar to the items in question.

CF can be used to make recommendations for basically any kind of data (e-commerce, videos, music, etc.).
The notebook contained in this repo is a part of a study on recommender systems using the [MovieLens 20M dataset](https://www.kaggle.com/grouplens/movielens-20m-dataset) from Kaggle as a proof of concept and implements/evaluates both kinds of collaborative filtering.
 

