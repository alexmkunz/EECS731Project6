# EECS 731 Project 6: Anomaly Detection
Detect anomalies in a dataset that contains the number of tweets mentioning Facebook in 5-minute intervals.

## Data Set
**Twitter_volume_FB.csv**: a dataset that contains the number of tweets mentioning Facebook in 5-minute intervals

## Juypter Notebook
**wordWideProductsInc.ipynb**:
 - **Exploratory Data Analysis:** show a lineplot of the number of tweets mentioning Facebook for the entire dataset, a month, a week, and a day.
 - **Anomaly Detection Models:** use IQR and isolation forests.
 - **Feature Engineering:** add average hourly/daily values to the dataframe. This ended up preventing our model from detecting very brief anomalies.
 
 ## Conclusion
 Isolation forests, unlike IQR, allow you to determine how many anomalies are in your dataset. 
