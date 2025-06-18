
**Airbnb NYC EDA Project**

Overview

This project performs an Exploratory Data Analysis (EDA) on the Airbnb NYC dataset to uncover insights into pricing, room types, location distributions, and host behaviors. The dataset contains over 48,000 listings with a mix of numerical and categorical features.

**Problem Statement**

Airbnb hosts and users generate large volumes of data daily. Understanding this data is essential for improving customer experience, optimizing prices, and guiding business decisions. This project aims to analyze the Airbnb listings in New York City to identify:

Key pricing trends

Popular room types

High-activity neighborhoods

Influential hosts

Dataset Description

Total Entries: 48,895

Total Features: 16

Feature Types: Numerical, Categorical, and Datetime

Tools and Libraries Used

Programming Language: Python

Data Handling: pandas, numpy

Data Visualization: seaborn, matplotlib

Environment: Jupyter Notebook

**Steps Performed**

1. Data Loading and Inspection

Loaded the CSV file using pandas

Viewed structure with df.head(), df.info(), df.describe()

2. Data Cleaning

Converted last_review to datetime

Filled missing values for name, host_name, and reviews_per_month

Verified and removed duplicate entries

3. Exploratory Data Analysis

Conducted analysis on the following:

Price distribution

Room types

Neighbourhood group frequency

Availability vs Reviews

Price vs Availability

Host activity

**Key Insights**

Most listings are priced between $50–$200

Manhattan dominates both in number and price of listings

Entire home/apt is the most preferred room type

Some hosts control hundreds of listings

No strong relationship between price and availability

**Visualizations Summary**

Histogram – Airbnb Price Distribution

Scatter Plot – Geographical Distribution of Listings

Bar Chart – Room Type Count

Pie Chart – Listings by Neighbourhood Group

Scatter Plot – Availability vs Number of Reviews

Scatter Plot – Price vs Availability

Bar Chart – Top 10 Hosts by Listings

Bar Chart – Average Price by Neighbourhood Group

**Conclusion**

This EDA helped identify patterns in Airbnb NYC data that can support pricing strategies, platform growth, and customer behavior understanding. Future work could involve predictive modeling and interactive dashboards.

