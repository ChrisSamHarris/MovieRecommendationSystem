# MovieRecommendationSystem

Machine Learning: Three primary types of recommendation systems:
- **Popularity based recommendation system** -> List of most-popular movies | Same for Amazon (most popular products)
    * Data Science
    * Utilising IMDB's "Rated Weighting Algorithm" = (WR) = (v ÷ (v+m)) × R + (m ÷ (v+m)) × C 

- **Content-based filtering**: Click a product and similar products are linked accordingly 
    * Data Science
    * Utilising comparsions dependent on Description of the movie

- Once the system understands some user information, what you watch, what you like:
    * Netflix / Amazon can align you with users who have a similar viewing pattern who highly rate X product 
    * **Collaborative filtering** 
    * Machine Learning 
    * Dataset -> Trainset -> ML Model -> Prediction 

### Utilising lambda 

Content based filtering notebook = `sorted(scores, key=lambda x: x[1], reverse=True)`, this lambda is used to essentially sort the second set of enumerated values at index 1, rather than the default of 0.

Lambda is a small anonymous function that can have any number of arguments, but only one expression = `lambda arguments: expression`

Simple lambda -> `f = lambda x, y: x + y`

We've utilised the lambda with a built in function a similar equation is as follows:
`points = [(1, 2), (3, 1), (2, 4)]`
`sorted_points = sorted(points, key=lambda p: p[1])`

Final example: 
`max_value = lambda x, y: x if x > y else y`
`print(max_value(4, 5)) `
