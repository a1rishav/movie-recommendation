# movie-recommendation
It remommends movies. A user just has to provide ratings of 10 or more movies to the app and returns you a list of movies that you will like. The concept is simple and it works like this, when you rate movies the app looks for other users whose ratings were like yours for the movies you rated. If there are a set of users whose ratings matches with yours for the same movies, it implies that you share similar taste for movies, so there is a chance that the movies that they have highly rated will be liked by you too. This is how Alternating Least Square algorithm works. 
The app uses Apache Spark and the Spark ML library.

## Tip
When the app recommends you movies you can rate it and feed it back in as input and recommendations will get better.
