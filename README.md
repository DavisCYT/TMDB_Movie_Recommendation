# TMDB_Movie_Recommendation
A project of build movie recommenders based on the movie input by the user.

**Two Recommendation Systems Are Built:**

**Demographic Filtering**
* The most simple and general recommendation system.
* The movies are ranked based on their weight-average voting score.
* Only movies with a number of votes equal or more than the first quantile range are used.
* Movie is recommended based on that voting score regardless of the movie input by user.

**Content Based Filtering**
* Recommend movie similar to the movie the user likes.
* ['overview','cast', 'crew', 'keywords', 'genres'] are the features being used to calculate the similarity of movie to each other.
