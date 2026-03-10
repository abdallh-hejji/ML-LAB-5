# ML-LAB-5
ARTI308 – Lab 5
Overview

In this lab I worked on feature engineering using the Talabat orders dataset. The goal was to create new features and see how they affect the performance of a machine learning model that predicts the order status.

What I Did

First, I explored the dataset and cleaned the data. Then I created some new features to help the model learn better patterns.

I extracted the order hour from the order time to understand when people usually place orders. I also created a peak hour feature to indicate busy times during lunch (11–14) and dinner (18–21).

I added a new engineered feature called distance_per_item, which divides the delivery distance by the quantity of items in the order. This helps represent how far the driver travels for each item.

For the food items, I kept only the most frequent ones and grouped the rest into “Other” to reduce the number of categories.

Model

I used a Random Forest classifier to train the model and predict the order status. After that, I applied feature selection using feature importance to keep only the most useful features.

Conclusion

This lab showed how feature engineering can help improve machine learning models by creating meaningful features and reducing unnecessary ones.
