#  Customer Bookings Prediction

* Scraped and analysed customer review data using Python to uncover key insights.
* Developed a random forest model with Python's scikit-learn to understand factors influencing buying behavior.

## Task 1: Sentiment Analysis: Customer Review Data

- The word cloud highlights key air travel terms such as "flight," "seat," "service," "time," ,"staff," "food," and "business class."

- Out of 1000 reviews, sentiment analysis reveals over 60% positive reviews and nearly 40% negative reviews.

In conclusion, focusing on improving food quality and seating conditions could significantly enhance overall customer satisfaction and improve the travel experience.

![Word_Cloud_and_Plority](https://sennanliimages.blob.core.windows.net/customer-bookings-prediction-project/Word_Cloud_and_Plority.png)

## Task 2: Build a predictive model to understand factors that influence buying behaviour

### Model Evaluation

- **High Accuracy (85%)**: Overall, the model is performing quite well, getting most predictions right.

- **Imbalanced Performance**: The model does an excellent job with Class 0 (‘booking_complete’ == False), but struggles with Class 1 (‘booking_complete’ == True), especially with a recall of 7%, primarily due to the imbalance in class distribution.

### **Top Features**:

- **Purchase Lead (**that is the time between purchase and departure**)**: Most influential. 

- **Flight Hour**: Highly impactful.

- **Length of Stay**: Significant influence.

- **Flight Duration**: Important.

- **Flight Day**: Notable contribution.

![Feature_Importance](https://sennanliimages.blob.core.windows.net/customer-bookings-prediction-project/Feature_Importance.png)
