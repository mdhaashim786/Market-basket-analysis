# Market-basket-analysis
This project shows how you can predict which items a shopper will purchase whether they buy it again or recommend to try for the first time.

The link for the dataset : https://www.kaggle.com/c/instacart-market-basket-analysis/data

This dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, it provides between 4 and 100 of their orders, with the sequence of products purchased in each order. It also provided the week and hour of day the order was placed, and a relative measure of time between orders.

This project comes under the domain of Big data with Spark implemented in the databricks environment.

The languages used are Python and SQL.

I have used Amazon S3 bucket to load the data into databricks file storage.

I have used data mining technique called FPM(Frequency pattern Mining). I used FP-Growth algorithm for analysing the frequency of the items purchased by the customers.

The complete project can be viewed under databricks cloud server. The link is https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4980803532271288/2138623309292248/6114357362569377/latest.html
