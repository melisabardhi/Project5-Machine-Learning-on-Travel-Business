# Machine Learning on a Travel Business
This project aims to analyze data on a travel business' booked venues in order to predict cancellations and classify transactions. 

## 1) Predict Venue Cancellations
Business goal: Study patterns in customer order cancellations, determine order importance and predict when a cancellation is likely to occur so that venues are prepared to find new bookings for empty space.

Machine Learning: 
- Explore data and perform feature engineering to increase correlation.
- Measure the accuracy of Logistic Regression, Support Vector Machine, Decision Trees, Random Forest, K-Nearest Neighbors and Neural Network in predicting a cancellation.

### Cancellations are less likely for venues with higher ratings and for those booked for domestic travel.
[![1.png](https://i.postimg.cc/d1yDRQ0W/1.png)](https://postimg.cc/47XJsgVt)

### Result: A cancellation happens 32% of the time and the Decision Tree was best at predicting it with an F1 of .37.


## 2) Classify Bookings
Business goal: Segment customers into clusters to effectively market to them so they are motivated to book venues which meet their personalized needs.

Machine Learning: 
- Use K-means and principal component analysis to cluster bookings in similar groups.
- Measure the performance of 5 algorithms using F1 score and processing time. 
- Perform gridseach on the best 3 algorithms (Decision Tree, Random Forest and K-Nearest Neighbors) to determine optimal hyper-parameters.


### Clusters 0 and 3 were the most differentiated in terms of reviews and price.
[![3.png](https://i.postimg.cc/Hs42dB3Z/3.png)](https://postimg.cc/PPJZMbgY)

### Result: The Random Forest was 56% more predictive than a dummy model.
