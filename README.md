# Movie-Recommendation
- Generated Top-10 movie recommendations for each user based on user ratings from MovieLens Latest Datasets.

  - Implemented an Alternative Least Squares (ALS) model with regularization from 0.05 to 0.8 and set cold start strategy to avoid NaN evaluation metrics.
  - Optimized the model hyperparameters with Spark ML cross-validation. The best model (RMSE = 0.9) has 14 latent factors and a regularization value of 0.2 within total runtime of 457 seconds on cloud-based platform.

*The original code was finished on Databricks with cloud-based big data processing using Spark*

 
### Part2: Spark ALS based approach for training model
#### ALS: Alternative Least Squares:
- Recommender systems, aka information recommender system, is a family of methods that enable filtering through large observation and information space in order to provide recommendations in the information space that user does not have any observation, where the information space is all of the available items that user could choose or select and observation space is what user experienced or observed so far. [Recommender systems](https://en.wikipedia.org/wiki/Recommender_system) typically produce a list of recommendations in one of two ways – through collaborative filtering or through content-based filtering (also known as the personality-based approach).
- 
