* *Author*: SatishReddy Bathula
* *Term*: Summer 2023
* *PPT*:(https://github.com/satishcz12651/Satish_data606/blob/main/docs/Review%20Prediction%20and%20Sentiment%20Analysis%20on%20Yelp%20Dataset.pptx)
* *Youtube*: (https://www.youtube.com/watch?v=I9H5FAiKEj0)
* *Github*:(https://github.com/satishcz12651/Satish_data606)
# Background #
The Yelp dataset I have chosen for this project due to its rich and diverse data on businesses, reviews, and user information. With comprehensive details on restaurants including location, categories, ratings, and reviews, the dataset offers practicality and real-world relevance. Moreover, the dataset presents a challenging and comprehensive task for building a restaurant recommendation and rating prediction system, involving textual data, user preferences, and diverse rating behaviors. By using the Yelp dataset, I can explore various algorithms and techniques in natural language processing, machine learning, and recommendation systems. Ultimately, working with this dataset provides learning opportunities and allows me to research in these fields. Overall, the richness, relevance, popularity, and challenges offered by the Yelp dataset make it a compelling choice for developing an effective restaurant recommendation and rating prediction system.
## [Data Source:] https://www.yelp.com/dataset
## Dataset Elements:
**Business_dataset:**

**business_id:** A unique identifier for each business.

**name:** The name of the business.

**address:** The street address of the business.

**city:** The city where the business is located.

**state:**  The state where the business is located.

**postal_code:** The postal code or ZIP code of the business location.

**latitude and longitude:**  The geographical coordinates of the business location.

**stars:** The average rating of the business on Yelp (ranging from 1 to 5 stars).

**review_count:** The number of reviews the business has received.

**categories:**  A list of categories or tags associated with the business.

**attributes:** Additional attributes or features of the business (e.g., whether it has Wi-Fi, accepts credit cards, etc.).

**is_open:** A flag indicating whether the business is open or closed.

**hours:** The operating hours of the business for different days of the week.

**Review_dataset:**

**review_id:** A unique identifier for each review.

**user_id:** The user ID of the reviewer.

**business_id:** A unique identifier for each business.

**stars:** The rating given by the reviewer (ranging from 1 to 5 stars).

**text:** The text content of the review.

**useful:** The number of users who voted the review as useful.

**funny:** The number of users who voted the review as funny.

**cool:** The number of users who voted the review as cool.

**date:** The date the review was posted.
|Dataset | Rows | Columns
---|---|---
business| 50000 | 14
reviews | 50000 | 9
# Results of EDA #
![Top 10 Categories in Yelp Dataset](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Top10_Categories.png?raw=true)
![Average Rating Distribution](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Average_review%20Bar%20plot.png?raw=true)
![Distribution of state](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Distribution%20of%20state.png)
![Distribution of restaurants in florida](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Distribution%20of%20restaurants%20in%20florida.png)
![Percentage of restaurants by city](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Percantage%20of%20restaurants%20in%20different%20cities.png)
![Five star rating count](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Number%20of%205%20star%20ratings%20restaurants%20in%20florida.png)
![Word Cloud](https://github.com/satishcz12651/Satish_data606/blob/main/docs/wordcloud.png)
![Sentiment Distribution](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Count%20of%20reviews.png)
# ML Algorithm Results #
- Algorithm Used: Multinomial Naive bias algorithm
- ![Result](https://github.com/satishcz12651/Satish_data606/blob/main/docs/Accuracy.png)
# Result Example #
| User_id| Restaurants Recommended
----|----
pZQBUJDh7EbDnGb3j474cw|Cafe Con Leche,Chipotle Mexican Grill,Four Green Fields,O'Briens Irish Pub,The Pearl,Top Shelf Sports Lounge,Walmart Supercenter,Williams Sub Shop
zJKasF9p4b_CoVeXt5RvTg|The Pearl,Top Shelf Sports Lounge
# Learnings #
- Restaurants which has the highest average rating have the highest reviews given to the customers which means if the service is good people tend to give ratings.
- When you are dealing with huge data make sure you check the computational source because it will take a lot of time to work with the huge dataset.
- Feedback plays a crucial role in popularity as it attracts customers from different places.
# Future Scope #
- Can explore more recommendation algorithms like collaborative filtering and content-based filtering techniques.
- Mobile app development by considering User’s preferences and choices so that they can select the restaurant based on their interests.
- Exploring the integrating of geolocation and navigation features to guide users to their chosen restaurants and provide directions.
  





  




