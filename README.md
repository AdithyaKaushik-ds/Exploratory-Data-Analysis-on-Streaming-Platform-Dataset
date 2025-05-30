# Exploratory-Data-Analysis-on-Streaming-Platform-Dataset

📺 OTT Streaming Platform Data Exploration

This repository contains exploratory data analysis and basic feature engineering performed on an OTT streaming platform dataset. The analysis aims to uncover content trends, user preferences, and platform strategies by transforming, cleaning, and visualizing the data.


📌 Objective

To analyze and extract meaningful insights from the content catalog of a major OTT platform, focusing on trends in genres, release years, cast diversity, and country-wise content production.

🧰 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)

Google Colab

Kaggle Dataset

🧪 Key Exploratory Tasks
Data Cleaning:

Handled missing values: categorical fields filled with Unknown, numeric fields filled with 0

Feature Engineering:

Unnested multi-valued fields (cast, listed_in) using .explode()

Temporal Analysis:

Distribution and trends in content release years

Content Categorization:

Genre-based insights

Country-wise distribution of shows

📊 Insights & Findings
Dataset contains 8,807 entries, spanning from 1925 to 2021

Median content release year is 2017, with the bulk of content added post-2010

Skewed distribution towards recent years suggests platform emphasis on new content

Content categories and cast diversity expanded through multi-row unnesting

Missing values appropriately imputed to preserve analysis integrity

📌 Future Work
Recommendation engine based on genre similarity

Viewer sentiment analysis using reviews (if available)

Integration with IMDb for enriched metadata

