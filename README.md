# CodeAlpha Data Analytics Internship - Task 1: Web Scraping

## Project Overview

This project was completed as part of the CodeAlpha Data Analytics Internship. The objective of the project is to collect data from a website using web scraping techniques and store the extracted information in a structured format for analysis.

## Objective

To extract book details such as title, price, and rating from a website using Python and save the collected data into a CSV file.

## Tools and Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Google Colab

## Data Collected

The following information was extracted from the website:

* Book Title
* Price
* Rating

## Project Workflow

1. Connected to the website using the Requests library.
2. Retrieved the HTML content of the webpage.
3. Parsed the HTML using BeautifulSoup.
4. Extracted book details including title, price, and rating.
5. Stored the extracted data in a Pandas DataFrame.
6. Exported the final dataset to a CSV file named `books.csv`.

## Output

The extracted data was successfully saved in CSV format and can be used for further analysis and visualization.

## Learning Outcomes

* Understanding of web scraping concepts.
* Working with HTML elements and tags.
* Data extraction using BeautifulSoup.
* Data storage and processing using Pandas.
* Exporting structured data to CSV format.




# CodeAlpha Data Analytics Internship - Task 2: Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of the CodeAlpha Data Analytics Internship. The main objective of this project is to perform Exploratory Data Analysis (EDA) on a sales dataset and identify meaningful patterns, trends, and insights using Python.

## Objective

To analyze sales data and gain insights by examining the dataset, calculating statistical measures, identifying patterns, and visualizing the data using charts and graphs.

## Tools and Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Dataset Description

The dataset contains sales transaction information including:

* Order ID
* Category
* Sales Amount

The dataset was used to understand sales performance and category-wise trends.

## Analysis Performed

### 1. Dataset Overview

* Loaded the dataset using Pandas.
* Examined the first few records using `head()`.

### 2. Data Information

* Checked column names and data types.
* Reviewed the overall structure of the dataset using `info()`.

### 3. Statistical Summary

* Generated descriptive statistics using `describe()`.
* Analyzed count, mean, minimum, maximum, and standard deviation values.

### 4. Missing Value Analysis

* Checked for null or missing values using `isnull().sum()`.

### 5. Sales Analysis

* Calculated Total Sales.
* Calculated Average Sales.
* Compared sales across different categories.

### 6. Data Visualization

* Created a histogram to visualize sales distribution.
* Created a bar chart to compare category-wise sales.

## Key Insights

* Identified total sales generated from the dataset.
* Determined the average sales value.
* Compared performance across different product categories.
* Visualized sales trends through graphical representations.

## Output Files

* EDA.ipynb
* sales_data.csv

## Learning Outcomes

Through this project, I learned:

* Data cleaning and exploration techniques.
* Descriptive statistical analysis.
* Handling missing values.
* Creating visualizations using Matplotlib and Seaborn.
* Extracting business insights from raw data.

  

# CodeAlpha Data Analytics Internship - Task 4: Sentiment Analysis

## Project Overview

This project performs sentiment analysis on customer reviews using Python. The objective is to classify reviews as Positive, Negative, or Neutral based on the words present in the review text.

## Objective

To analyze customer feedback and determine the sentiment expressed in each review.

## Tools and Technologies Used

* Python
* Pandas
* Google Colab

## Dataset

The dataset contains customer review comments stored in a CSV file.

### Dataset Column

* Review

## Methodology

1. Imported the dataset using Pandas.
2. Created a sentiment classification function.
3. Defined positive and negative keywords.
4. Analyzed each review.
5. Assigned a sentiment label:

   * Positive
   * Negative
   * Neutral
6. Saved the results to a new CSV file.

## Output

The output file contains:

* Review
* Sentiment

## Key Insights

* Positive reviews indicate customer satisfaction.
* Negative reviews highlight customer concerns.
* Neutral reviews provide balanced feedback.
* Sentiment analysis helps businesses understand customer opinions.

## Files Included

* Task4_SentimentAnalysis.ipynb
* reviews.csv
* sentiment_output.csv
* README.md

## Learning Outcomes

* Data preprocessing using Pandas
* Text analysis fundamentals
* Sentiment classification
* Working with CSV files
* Data analytics project documentation

## Internship Program

CodeAlpha Data Analytics Internship

## Author

THIRUMALINI P



