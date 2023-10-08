## Conversion_Comparison

#### Technology Stack:
BigQuery (CTE, regular expressions, data aggregation, function, joins)

#### Project Description:
In this project, I utilized BigQuery to analyze conversion data from a publicly available dataset collected using Google Analytics 4, specifically from the Google online store.

To accomplish this, I extracted page paths (the path to the page without domain addresses and link parameters) from the session start events.

For each unique session start page, I calculated the following 2020-based metrics:
1. The number of unique sessions among distinct users.
2. The number of purchases.
3. The conversion rate from session start to purchase.

Since session start and purchase events can have different URLs, I merged them using user IDs and session IDs for accurate analysis.

[BigQuery Link](https://console.cloud.google.com/bigquery?sq=916069414937:a9cbf36489684530aafcc282f37fcde6)

[Source data from GA 4](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=ga4_obfuscated_sample_ecommerce&t=events_20210131&page=table&project=hardy-scarab-392910)

#### Skills:
Data Analysis · SQL · Google BigQuery · Google Analytics 4 · Big Data · Big Data Analytics
