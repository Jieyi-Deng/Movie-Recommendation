# Movie-Recommendation
- Generated Top-10 movie recommendations for each user based on user ratings from MovieLens Latest Datasets.

  - Developed a data ETL pipeline to explore approx. 100 million movie ratings and cleaned the data by removing invalid ratings, null user ID, etc.
  - Implemented an Alternative Least Squares (ALS) model with regularization from 0.05 to 0.8 and set cold start strategy to avoid NaN evaluation metrics.
  - Optimized the model hyperparameters with Spark ML cross-validation. The best model (RMSE = 0.9) has 14 latent factors and a regularization value of 0.2 within total runtime of 457 seconds on cloud-based platform.

*The original code was finished on Databricks with cloud-based big data processing using Spark*




### Part1: Data ETL and Data Exploration
#### A:
- 

-   
### Part2: Spark ALS based approach for training model
