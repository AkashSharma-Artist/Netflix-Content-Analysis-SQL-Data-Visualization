# Netflix Content Analysis – SQL + Data Visualization

![](https://github.com/AkashSharma-Artist/Netflix-Content-Analysis-SQL-Data-Visualization/blob/main/logo.png)

## Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows 
data using SQL. Beyond writing queries, this project also includes designing a 
structured relational table schema and building visual dashboards/charts to 
present the findings in an easy-to-understand format — going from raw data to 
query-based insights to visual storytelling.

## Objectives
- Analyze the distribution of content types (movies vs TV shows).
- Identify the most common ratings for movies and TV shows.
- List and analyze content based on release years, countries, and durations.
- Explore and categorize content based on specific criteria and keywords.
- Design a clean, structured table schema to organize raw data.
- Visualize key findings through charts for quicker, non-technical interpretation.

[... existing schema, business problems & solutions sections (Q1-Q15) stay as-is ...]

## Table Design
As part of this project, a structured table (`netflix`) was created with 
appropriate data types for each field (show ID, type, title, director, cast, 
country, release year, rating, duration, genre, and description) — ensuring 
clean, query-ready data before any analysis began.

## Visualizations
To make the findings more accessible, key insights from the SQL queries were 
also converted into visual charts, including:
- Content type distribution (Movies vs TV Shows)
- Top 5 countries by content volume
- Genre-wise content count
- Top 10 actors by number of Indian movie appearances
- Content categorization (Good vs Bad, based on keyword analysis)

![](https://github.com/AkashSharma-Artist/Netflix-Content-Analysis-SQL-Data-Visualization/blob/main/IMG.png)

These visuals complement the raw SQL output, making the analysis easier to 
present to non-technical stakeholders.

## Findings and Conclusion
- **Content Distribution:** The dataset contains a diverse range of movies and TV shows with varying ratings and genres.
- **Common Ratings:** Insights into the most common ratings provide an understanding of the content's target audience.
- **Geographical Insights:** The top countries and the average content releases by India highlight regional content distribution.
- **Content Categorization:** Categorizing content based on specific keywords helps in understanding the nature of content available on Netflix.
- **Schema Design:** A well-structured table schema ensured data integrity and made complex queries (window functions, string parsing) easier to write and maintain.
- **Visualization:** Converting query results into charts made the insights significantly easier to communicate to non-SQL audiences, bridging the gap between raw analysis and business reporting.

This analysis provides a comprehensive view of Netflix's content — combining 
SQL querying, structured data modeling, and visualization — and can help 
inform content strategy and decision-making.
