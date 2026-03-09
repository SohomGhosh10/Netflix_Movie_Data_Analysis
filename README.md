Netflix Movie Data Analysis Dashboard

An interactive Netflix-style content analytics dashboard built using Google Sheets and Microsoft Excel.
This project analyzes a synthetic Netflix-style dataset to extract insights related to content distribution, financial performance, and audience ratings.

The workflow includes data cleaning, pivot-table analysis, and dashboard visualization, resulting in a concise analytical dashboard useful for exploratory reporting and decision-making.

Project Overview

This project explores a Netflix-like catalog containing 1040 content records with attributes such as:

Content Type

Genre

Production Budget

Box Office Revenue

IMDb Rating

Country of Origin

Language

The dataset was analyzed using Excel pivot tables and charts to identify trends and build a visual dashboard summarizing key insights.

Key Objectives

Analyze the distribution of Netflix content types

Compare production investment vs box office returns

Evaluate average duration and IMDb ratings

Identify top producing countries and languages

Transform raw data into dashboard-ready analytics

Present insights through pivot charts and KPI summaries

Project Structure:

Netflix_Movie_Data_Analysis
│
├── Raw Dataset
│   └── Movies.csv
│
├── Cleaned Dataset
│   └── Clean movies.xlsx
│
├── Dashboard Excel File
│   └── Netflix Dashboard.xlsx
│
├── Dashboard
│   └── Dashboard Screenshot.png
│
└── README.md


Dataset Summary
Metric	Value
Total Records	1040
Total Columns	18
Missing Values	0
Release Year Range	1953 – 2024
Netflix Originals	318
Content Warning Titles	201
Financial Metrics
Metric	Value
Total Production Budget	$11.56 Billion
Total Box Office Revenue	$67.19 Billion
Revenue to Budget Ratio	5.81x
Content Type Distribution
Content Type	Count	Percentage
Movie	458	44.04%
TV Series	267	25.67%
Documentary	142	13.65%
Stand-up Comedy	119	11.44%
Limited Series	54	5.19%

Movies dominate the dataset, accounting for nearly half of all content.

Top Languages
Language	Count
English	608
Spanish	103
French	67
Hindi	60
Japanese	55
Top Producing Countries
Country	Content Count
USA	543
South Korea	118
Canada	102
UK	88
Japan	57
Dashboard Preview

Add your dashboard screenshot here.

![Dashboard](Dashboard/Dashboard Screenshot.png)

This allows viewers to see the dashboard directly on GitHub.

Analytics Insights

The pivot analysis focuses on:

Content Type Analysis

Content count by type

Average duration

Average IMDb rating

Production budget comparison

Box office revenue comparison

Country Level Analysis

Content production by country

Investment distribution

Revenue generation comparison

Tools Used

Google Sheets

Microsoft Excel

Pivot Tables

Pivot Charts

Dashboard Visualization

Data Cleaning Notes

Several transformations were applied to prepare the dataset for analysis:

movie_id split into two columns

Titles removed in cleaned dataset to simplify pivot tables

Date values stored using Excel serial format

Duplicate checks performed

Observed issues in raw dataset:

40 duplicate movie IDs

262 duplicate titles

Series metrics mostly zero for non-series content

Conclusion

The analysis reveals several key patterns within the dataset.

Movies represent the largest share of content, making up over 44% of the catalog, indicating a strong focus on film production. Financial analysis shows a significant return on investment, with total box office revenue exceeding production budgets by more than 5.8 times.

The dataset also highlights the dominance of English-language content and United States productions, although countries like South Korea, Canada, and Japan contribute notable volumes of content.

Overall, this project demonstrates how Excel pivot tables and dashboards can transform raw entertainment industry data into actionable insights. The techniques used here can be applied to real-world streaming platform analytics and business intelligence scenarios.
