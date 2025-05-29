# Zomato-Restaurant-Data-Analysis

This project focuses on exploratory data analysis (EDA) and visualization of the Zomato restaurant dataset, which includes restaurant-level information across various countries. The goal is to extract key insights from the data that can help Zomato and similar platforms make informed business decisions, improve user experience, and understand global food market dynamics.

The dataset includes restaurant-related attributes such as name, location, cuisine types, user ratings, delivery options, and pricing. Additionally, it’s joined with a supplementary dataset containing country codes, enabling a deeper geographical analysis.

The project begins with importing essential Python libraries like pandas, numpy, matplotlib, and seaborn. The primary Zomato dataset (zomato.csv) is read and merged with the Country-Code.xlsx file using the Country Code as the key, resulting in a unified dataset named final_df.

The initial steps involve inspecting the dataset's structure and cleaning it. This includes checking the shape, data types, null values, and basic descriptive statistics. Data quality is evaluated by identifying missing values and understanding variable distributions.

The core part of the project involves detailed exploratory data analysis (EDA):

Country-wise Analysis: The analysis reveals that most data entries are from India, followed by the United States and the United Kingdom. A pie chart helps visualize the distribution of restaurants across top contributing countries.

Rating Distribution: Ratings are grouped by their aggregate values, associated colors, and textual labels like 'Excellent', 'Good', or 'Poor'. It is observed that the majority of entries are unrated, and most ratings fall between 2.5 to 3.4. A barplot colored by rating levels visually supports this inference.

Zero Ratings: The dataset highlights countries where users have not provided ratings. Notably, the UAE and India appear in the ‘White’ color rating segment, indicating no ratings.

Currency Mapping: A cross-tab of countries and their respective currencies helps in understanding international pricing variations and preparing Zomato for global financial integrations.

Online Delivery Analysis: Countries like India show a significantly higher number of restaurants offering online delivery, suggesting maturity in food delivery ecosystems. This insight can guide Zomato's strategic expansion and product enhancements.

City Distribution: A pie chart reveals the top 5 cities with the most restaurants, with New Delhi leading by a large margin.

Cuisine Analysis: Using value counts and text processing, the project identifies the top 10 cuisines offered by restaurants. This analysis helps understand regional food preferences and can assist in tailoring recommendations or launching cuisine-specific campaigns.

Throughout the project, various types of visualizations—bar plots, pie charts, and count plots—are used to simplify complex data patterns and make the insights more interpretable.

In conclusion, this project provides actionable insights such as the most dominant countries, cities, rating behavior, and popular cuisines in the Zomato dataset. It demonstrates how EDA can unlock business intelligence from raw data. These insights can help Zomato optimize its operations, enhance customer engagement, and make data-driven decisions regarding market entry strategies, partnerships, and user interface features.
