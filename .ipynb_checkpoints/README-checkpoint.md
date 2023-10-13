# MovieRecommendationSystem

Machine Learning: Three primary types of recommendation systems:
- **Popularity based recommendation system** -> List of most-popular movies | Same for Amazon (most popular products)

- Once the system understands some user information, what you watch, what you like:
  * Netflix / Amazon can align you with users who have a similar viewing pattern who highly rate X product 
  * **Collaborative filtering** 

- **Content-based filtering**: Click a product and similar products are linked accordingly 

### Utilising Lambda 

Content based filtering notebook = `sorted(scores, key=lambda x: x[1], reverse=True)`, this lambda is used to essentially sort the second set of enumerated values at index 1, rather than the default of 0.

