# DSA4212-Anime-Recommendation-System

**Contributors**: Sneha Kumar, Ee Wei En Barnabas, Han Xiao Guang 

**Goal**: Build a recommender system to predict the user ratings, in the range of 1 to 10, for a list of animes. 

**Dataset**: The provided training dataset consists of approximately 4.4 million user-anime ratings while the testing dataset consists of approximately 2 million user-anime ratings. The testing dataset also contains new user and anime IDs that are not found in the training dataset, meaning that the recommender system has to be able to predict ratings for unseen users and animes.

**Experiments with Non-Factor Models**: Random Uniform, Random Distribution, Global Average, User Average, Anime Average, Equal/Unequal Weighted Average, Genre Average, Co-clustering, Slope one, Wide-Deep

**Experiments with Factor Models**: Low-Rank Matrix Factorization, Non-negative Matrix Factorization, Ensembling of Factor Models with Average models, Factor on residuals, SVD (Surprise), Ensembling of SVD with Slope One/Co-clustering 

**Final Results**: Test MSE of 1.295
