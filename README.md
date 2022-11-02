# Movie-recommender-systems

The growth of e-commerce websites recently emerged the importance of recommender systems, where thes websites use customer's interests to generate recommended products and items. Customer's behaviors such as purchases, views, and ratings are crucial for many web-apps in order to recommend their users similar items based on these behaviors. Recommender systems have become useful tools for users by providing custom recommendations on items.

This notebook discuss the most commonly used filtering techniques for Recommeder Systems.

### Content–Based Filtering (CBF)
Content-based filtering uses item features to recommend other items similar to what the user likes, based on their previous actions or explicit feedback.

**- Movie-Plot Based Recommender** which recommend movies based on the pairwise similarity score of the movies overview.

**- Cast, Keywords and Genres Based Recommender** Considered adding more feature to the model such as `df[["cast", "crew", "keywords", "genres"]]` to increase the quality of the recommender.

### Collaborative Filtering (CF)
The previous models are not personalized, meaning that it doesn't take the user interest or taste in consideration. 
Collaborative Filtering can deal with that issue since it depends on the history of the user's behaviour and the interaction with items.
The user interaction with items can be either explict like giving rating or feedback to an item or implict as clicks or views.

**- Matrix Factorization Based Recommender**: A Collaborative Filtering method for generating latent features for two kinds of entities. Latent features are computed to
to find the similarity between items then make predictions.


