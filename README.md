# Sp24_Machine-Learning-Notebooks2

# Week 4

# Kernel Methods & SVMs

# SVM for Regression 

1. The objective is to fit as many instances as possible with the margin whose width is still controlled by hyperparameter
2. Adding more training instances does not affect the model's prediction- hence the model is insensitive to the margin width

# SVM in scikit-learn

<img width="456" alt="Screenshot 2024-04-21 at 8 12 00 PM" src="https://github.com/ColleenJung/Sp24_Machine-Learning-Notebooks2/assets/119357849/ff3faf85-6d18-4681-8c8b-cd8aa8a01c3b">

- **C is essentially a regularization parameter,** which controls the trade-off between achieving a low error on the training data and minimizing the norm of the weights

# Collaborative Filtering (CF) Recommendation

- used to predict preferences
- Rootoed in information filtering that uses group opinions for recommendation aka Recommender

# User-based or Item-based filtering

<img width="318" alt="Screenshot 2024-04-21 at 8 44 02 PM" src="https://github.com/ColleenJung/Sp24_Machine-Learning-Notebooks2/assets/119357849/f45bc443-4ca8-494f-88b7-440829473c44">

- User based: database of preferences for items by users and a **new user is matched against the databased to find neighbors who have similar preferenced and recommend items preferred by the nieghbors to the new user**
- Item based: **based on similar items rather than similar neighbours,** rates items to similar items and combines the similar items into a recommendation.

1. **Item-based recommenders are easier to maintain** in terms of compute requirement (especially for large catalogues) as similarity estimates between items are more likely to converge over time and are relatively static than similarities between users.
2. **Item-based recommenders have speed performance advantage** since in user-based recommenders matrix recalculation happens more often as user addition/removal is more dynamic than items.
3. **User-based recommenders are simpler to implement** since item-based recommenders start with a list of a user's preferred items and then calculate the item similarities matrix.

# Content-Based (CB) Recommendation

1. Content based recommendation – analytical description of the characteristics of content/item.
2. Match a user to the content characteristics as opposed to other users.
3. To figure out how songs are simiar Pandorma implement 

