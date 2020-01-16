## Recommendation Engines


### Description
This project analyses the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they might like.

### Structure
1) Data Exploration
2) Rank Based Recommendations: find the most popular articles simply based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
3) User-User Based Collaborative Filtering: looking at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 
4) Matrix Factorization: machine learning approach to building recommendations. Using the user-item interactions, built out a matrix decomposition. Using the decomposition, you can get an idea of how well you can predict new articles an individual might interact with.

### Acknowledgments
Project with Udacity Data Scientist Nanodegree
