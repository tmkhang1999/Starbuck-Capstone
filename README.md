
![Starbucks Image](https://cdn.pixabay.com/photo/2017/01/11/17/05/starbucks-1972319_1280.jpg)
<h3 align="center">Starbucks Capstone</h3>
<p align="center">
  Unveiling Deeper Insights into Starbucks Customer Behaviors.
  <br>
  <a href="https://www.kaggle.com/datasets/ihormuliar/starbucks-customer-data"><strong>Explore Starbucks Dataset »</strong></a>
</p>

## Project Motivation<a name="motivation"></a>

This project aims to uncover valuable insights into Starbucks customer behaviors by analyzing simulated data from the Starbucks rewards app. Collaborating with Udacity and Starbucks, our goal is to drive effective marketing strategies and enhance customer satisfaction.

Through exploratory data analysis, we will clean the dataset and visualize key demographic information, including gender distribution, income levels, age distribution, and membership trends. By identifying patterns and trends, we can understand the factors that influence customer engagement with offers.

To predict factors impacting offer completion, we will develop a machine learning model, focusing on demographic variables. We will employ the LGBM Classifier and evaluate the F1-Score to enhance model accuracy and gain valuable insights.
## File Descriptions <a name="files"></a>
The data is contained in three files:
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

1. portfolio.json
```angular2html
id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)
```

2. profile.json
```
age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
```

3. transcript.json
```angular2html
event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record
```

## Results<a name="results"></a>
Click on this <a href="https://medium.com/@khangtm99/exploring-starbuckss-customer-behaviors-for-deeper-insights-823da0505e89">Medium Post</a> link to understand more about the data visualization

## Licensing<a name="licensing"></a>
The Starbucks dataset was downloaded from <a href="https://www.kaggle.com/datasets/ihormuliar/starbucks-customer-data">Kaggle</a> and is licensed under a <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License.</a>. 

The code in this repository is released under MIT License.

