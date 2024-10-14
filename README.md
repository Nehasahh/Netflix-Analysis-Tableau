# Project: Netflix Content Analysis Dashboard using Tableau

# Objective: 
To provide a comprehensive and interactive exploration of Netflix’s content library, highlighting regional popularity, trends, genre insights, and viewer interests.

# Data Cleaning and Preparation:
The project began with gathering the Netflix dataset, which contained raw information on shows, movies, ratings, genres, and regional preferences. Recognizing the importance of clean data for reliable analysis, I followed a systematic data cleaning process:

# Data Cleaning:
*Duplicate Removal: I identified and removed duplicate entries to ensure accuracy.
*Handling Missing Values: I carefully handled missing data points by either imputing them where possible or excluding them to avoid skewing the analysis.
*Standardizing Formats: I standardized date formats (e.g., release dates) and ensured consistency in categorical variables such as country names and genres.
*Data Enrichment: Additional relevant data like IMDb ratings were integrated to add depth to the analysis of ratings and trends.

# Data Manipulation:
*Creating New Metrics: I derived new fields, such as 'Years Since Release,' to analyze trends over time.
*Aggregation: I aggregated data by country, genre, and year to enable comparisons across these dimensions.

# Data Analysis and Exploration:
After cleaning, I performed an exploratory data analysis (EDA) to identify key patterns and correlations within the dataset:

*Regional Popularity: I analyzed which shows and movies were the most popular in specific regions, uncovering viewing patterns unique to various countries.
*Trend Analysis: By studying the evolution of Netflix ratings and popularity over the years, I was able to track shifts in viewer behavior and content preferences.
*Genre Insights: I analyzed viewer interest across genres, identifying the top 10 trending genres and uncovering hidden patterns in genre popularity.

# Dashboard Creation and Insights Visualization:
After data cleaning and EDA, I uploaded the cleaned dataset into Tableau and created an interactive, visually engaging dashboard to present insights:

*Filters and Drill-Downs: The dashboard allows users to filter by region, genre, and year, enabling interactive exploration of Netflix’s diverse content.
*Regional Popularity Map: I utilized geographical maps to display the most popular shows and movies across different countries, providing a clear view of regional trends.
*Time Series Analysis: Using line charts, I illustrated how ratings and popularity have evolved over the years, highlighting significant trends.
*Genre Distribution: A bar chart was created to visualize viewer interest across genres, making it easy to identify the top 10 trending genres.
*Current Trends: To capture the latest content trends, I incorporated data filters allowing users to explore the most popular shows and movies currently trending on Netflix.

# Tools & Techniques Used:

*Data Cleaning & Manipulation: Excel
*Visualization: Tableau (with advanced features like interactive filters, geographical maps, and drill-downs)
*Analysis: Exploratory Data Analysis, Trend Identification, Genre Analysis
