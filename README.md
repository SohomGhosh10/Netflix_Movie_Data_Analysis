Netflix Movie Data Analysis Dashboard

An interactive Netflix-style content analytics dashboard built using Google Sheets and Microsoft Excel.
The project explores a synthetic Netflix-like dataset to uncover insights about content distribution, production investment, revenue performance, and audience ratings.

The analysis pipeline includes data cleaning, pivot-table based analytics, and dashboard visualization, resulting in a compact analytical dashboard that supports exploratory reporting and data-driven decision-making.

Project Overview

This project analyzes a Netflix-style content catalog containing over 1000 records. The dataset includes various attributes such as content type, production budget, box office revenue, IMDb rating, language, and country of origin.

The objective is to transform raw entertainment industry data into meaningful insights using Excel pivot analysis and dashboard visualization techniques.

The workflow followed in this project:

Raw data exploration

Data cleaning and validation

Pivot table analysis

Dashboard creation and visualization

The final dashboard provides a concise overview of content trends, financial performance, and rating comparisons across different content categories.

Key Objectives

Analyze the distribution of Netflix content types such as Movies, TV Series, Documentaries, and Stand-up Comedy

Compare production investment versus box office returns

Evaluate average duration and IMDb ratings by content category

Identify top contributing countries and languages

Develop a dashboard-ready analytical layer from the raw dataset

Present insights through visual pivot charts and KPI summaries

Project Structure
Netflix-Movie-Data-Analysis
│
├── Raw Dataset
│   └── Movies.csv
│
├── Clean Dataset
│   ├── Clean movies.xlsx
│   └── Clean movies - movies.pdf
│
├── Pivot Tables and Calculations
│   ├── Movies Pivot Data Analysis1.xlsx
│   └── Movies Pivot Data Analysis2.xlsx
│
├── Dashboard
│   └── Dashboard Screenshot.png
│
└── README.md


Data Dictionary
Column Name	Data Type	Description
movie_id	Text	Unique identifier in movie_#### format
title	Text	Name of the movie or series
content_type	Text	Category of content (Movie, TV Series, Documentary, etc.)
genre_primary	Text	Primary genre
genre_secondary	Text	Secondary genre
release_year	Integer	Year of release
duration_minutes	Integer	Runtime in minutes
rating	Text	Age certification rating
language	Text	Primary language of content
country_of_origin	Text	Country of production
imdb_rating	Decimal	IMDb score ranging from 0–10
production_budget	Decimal	Total production cost
box_office_revenue	Decimal	Revenue generated from box office
number_of_seasons	Integer	Number of seasons (for series content)
number_of_episodes	Integer	Number of episodes (for series content)
is_netflix_original	Boolean	Indicates whether the content is a Netflix Original
added_to_platform	Date	Date when the content was added to the platform
content_warning	Boolean	Indicates presence of content warnings
Data Summary

Total records: 1,040

Total columns: 18

Missing values: None

Release year range: 1953 – 2024

Platform addition range: Aug 2020 – Aug 2025

IMDb Rating Statistics

Minimum: 0.5

Maximum: 10.0

Average: 6.27

Netflix Originals

318 titles (30.58%)

Content Warning

201 titles (19.33%)

Financial Metrics
Metric	Value
Total production budget	$11.56 Billion
Total box office revenue	$67.19 Billion
Revenue-to-budget ratio	5.81x return
Content Type Distribution
Content Type	Count	Percentage
Movie	458	44.04%
TV Series	267	25.67%
Documentary	142	13.65%
Stand-up Comedy	119	11.44%
Limited Series	54	5.19%

Movies dominate the dataset, accounting for nearly half of all content entries.

Top Languages
Language	Count
English	608
Spanish	103
French	67
Hindi	60
Japanese	55

English-language content represents the majority of productions.

Top Producing Countries
Country	Count
USA	543
South Korea	118
Canada	102
UK	88
Japan	57

The United States leads the dataset, followed by South Korea and Canada.

Data Cleaning Notes

The cleaned dataset (Clean movies.xlsx) includes minor structural adjustments for analytical efficiency:

The movie_id field was separated into two columns: movie and id

The title column was excluded from analytical sheets to simplify pivot analysis

Dates were stored using Excel serial date format

Additional quality checks were performed on raw data

Observed Data Issues

40 duplicate movie IDs (each appearing twice)

262 duplicate titles, which may represent franchises or repeated naming

Series-related fields such as seasons and episodes are zero for non-series content

Analytics View

The pivot analysis workbooks include multiple pivot tables used to generate insights.

Pivot Table – Content Type Analysis

Metrics analyzed:

Total content count

Average duration

Average IMDb rating

Total production budget

Total box office revenue

Total seasons

Total episodes

Pivot Table – Country Level Analysis

Metrics analyzed:

Content count by country

Total investment by country

Total revenue generated by country

Dashboard Insights

The final dashboard includes several visualizations:

Content Type Distribution

Duration Comparison by Content Type

Average IMDb Rating by Content Type

Investment vs Return Analysis

Country-wise Investment vs Revenue Comparison

These charts provide a clear overview of content trends and financial performance within the dataset.

Tools Used

1. Google Sheets
2. Microsoft Excel
3. Pivot Tables
4. Pivot Charts

Data Cleaning Techniques

Dashboard Design

Conclusion

The analysis highlights several interesting patterns within the dataset.

Movies represent the largest share of content, indicating that film productions dominate the catalog compared to series or documentaries. Financial analysis shows a strong return on investment, with total box office revenue exceeding production budgets by more than 5.8 times, suggesting high profitability in the dataset.

Language and country distribution also reveal that English-language productions and the United States dominate the content landscape, though international markets such as South Korea and Japan also contribute significantly.

Overall, this project demonstrates how Excel pivot tables and dashboard visualizations can transform raw entertainment industry data into actionable insights. The approach used here can easily be extended to real streaming platform data for business intelligence and strategic decision-making.
