# Movie-Recommendation
- Generated Top-10 movie recommendations for each user based on user ratings from MovieLens Latest Datasets.

  - Implemented an Alternative Least Squares (ALS) model with regularization from 0.05 to 0.8 and set cold start strategy to avoid NaN evaluation metrics.
  - Optimized the model hyperparameters with Spark ML cross-validation. The best model (RMSE = 0.9) has 14 latent factors and a regularization value of 0.2 within total runtime of 457 seconds on cloud-based platform.

*The original code was finished on Databricks with cloud-based big data processing using Spark*

 
### Spark ALS based approach for training model
#### ALS: Alternative Least Squares:
- [Recommender systems](https://en.wikipedia.org/wiki/Recommender_system) typically produce a list of recommendations in one of two ways: [collaborative filtering](https://en.wikipedia.org/wiki/Collaborative_filtering) or through [content-based filtering](https://en.wikipedia.org/wiki/Recommender_system#Content-based_filtering) (also known as the personality-based approach).
- Collaborative filtering is commonly used for recommender systems. These techniques aim to fill in the missing entries of a user-item association matrix. spark.mllib currently supports model-based collaborative filtering, in which users and products are described by a small set of latent factors that can be used to predict missing entries. spark.mllib uses the alternating least squares (ALS) algorithm to learn these latent factors.
