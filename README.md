# Movie-Recommendation-System
I will just walk through all the steps that I have followed:
We need to choose the features we need to combine in order to predict the recommendations.
The features which I have combined are keywords, cast, genres, and director.
Suppose a user wants to watch a movie similar to Avengers then we can recommend the user by calculating the cosine similarity between Avengers and other movies.
Then I accessed the rows corresponding to the given movie to find all the similarity scores for that movie and then enumerating over it.
