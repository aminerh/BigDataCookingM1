# Big-Cooking-Data

This project consists of four main parts:

## A. Data Scraping
Website: Marmiton

1. Install the Scrapy library for Python. You can find detailed instructions on how to install it at: [https://scrapy.org/](https://scrapy.org/).

2. Once the library is installed, run the provided code to scrape the data from the Marmiton website. You can generate either a CSV or JSON file using the following command:

scrapy crawl marmiton -o test.json or test.json


This command will save the scraped data to the "output.json" file.

3. More detailed explanations on how the code works will be provided soon.

## B. Data Cleaning
The collected data needs to be cleaned to prepare it for clustering.

## C. Data Clustering
In this step, we use clustering algorithms such as K-means and PCA to cluster the cleaned data. These algorithms help identify patterns and group similar data points together.

## D. Data Insertion
The clustered data will be inserted into a MySQL database. Further details on the data insertion process will be explained soon.

Please note that the information provided above is a general overview of the project. More specific details and code explanations will be provided for each step in the future.

