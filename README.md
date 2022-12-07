# Bias in IBM advertising

This notebook is based on the synthetic dataset of user records created by **IBM** in order to find bias in advertising. The **AI Fairness 360 toolkit** was used in order to calculate the **predicted probability** and **conversion** from different feature attributes. The feature attributes that we kept from the inital dataset are **education status, homeownership, gender, age, and income** while the outcome variables were **true_conversion, predicted_conversion, and predicted_probability**. From the **1,443,140** records, we trimmed the dataset to **2390** records due to having too many null values in some feature attributes which led to these 5. For more information about the original dataset and the study, click [here](https://developer.ibm.com/exchanges/data/all/bias-in-advertising/)

The dataset was collected through IBM.

The models from feature importance were obtained from another article located [here](https://towardsdatascience.com/understanding-feature-importance-and-how-to-implement-it-in-python-ff0287b20285)

There were 5 feature attributes in the new_table.csv: college_educated, homeowner, income, age, and gender. 

college_educated - 0 = no college education, 1 = college educated

homeowner - 0 = doesn't own home, 1 = owns home

income - income is less than 100,000, >100K = income is more than 100,000

age - The age spans 4 categories: 18-24, 25-34, 45-54, 55-64

gender - M = Males, F = Females

There were 3 outcome variables: true_conversion, predicted_conversion, predicted_probability

true_conversion - 0 represents not clicking on the ad while 1 represents a conversion(clicking on the ad)

predicted_conversion - 0 represents not clicking on the ad while 1 represents a conversion(clicking on the ad)

predicted_probability - Predicted_probability is a decimal betwen 0 and 1 calculated by the AI Fairness 360 Toolkit

There are no potential risks or biases seen in the data so far. 
