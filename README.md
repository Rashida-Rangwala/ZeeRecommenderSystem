# ZeeRecommenderSystem
Personalized Movie Recommender System to Enhance User Experience

This project implements a movie recommender system based on user ratings data. It explores various techniques for generating personalized recommendations, including:

1. Collaborative Filtering:
  Item-based approach using Pearson Correlation and Cosine Similarity
  User-based approach using Pearson Correlation (Optional)
2. Matrix Factorization
3. Data Description

The project utilizes the MovieLens dataset, containing three files:

  ratings.csv: User ratings for movies (UserID, MovieID, Rating, Timestamp)
  users.csv: User demographic information (UserID, Gender, Age, Occupation, Zip-code)
  movies.csv: Movie information (MovieID, Title, Genres)
  
Project Structure
The project consists of Python scripts and files containing the downloaded MovieLens dataset.

Scripts:

Read data files, clean and format them into a single DataFrame.
Performed exploratory data analysis (EDA) to understand data structure and distribution.
Implemented item-based recommendation using Pearson Correlation and Cosine Similarity.
Implemented user-based recommendation using Pearson Correlation.
Implemented matrix factorization recommendation using Surprise library.
Visualized user and item embeddings for analysis.

Evaluation:

The project focuses on implementing various recommendation approaches. While some scripts include basic evaluation metrics (RMSE and MAPE) for Matrix Factorization.
