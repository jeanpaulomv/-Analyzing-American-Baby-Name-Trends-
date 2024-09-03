![Banner](images/Baby_Names_Banner_Image.png)

# Analyzing American Baby Name Trends

Explore American baby name trends using 101 years of data from the U.S. Social Security Administration. This project provides insights into the evolution of baby names and their popularity over time.

## Project Overview

This analysis investigates how baby name popularity has changed from 1920 to 2020. Key tasks include identifying timeless names, classifying names based on popularity, and examining trends for female and male names. The dataset includes names given to at least 5,000 babies per year.

## Skills Applied

- **SQL Queries**: Utilized complex SQL queries, including CASE WHEN, LIKE, subqueries, common table expressions (CTEs), and window functions to analyze data.
- **Data Analysis**: Employed techniques to classify, rank, and track trends in baby names over time.

## Key Insights

1. **Timeless Names**: Identified names that have remained popular across all 101 years.
2. **Popularity Classification**: Categorized names as 'Classic', 'Semi-classic', 'Semi-trendy', or 'Trendy' based on their appearance over the years.
3. **Top Female Names**: Ranked the top ten female names based on total number of babies named.
4. **Trendy Names**: Selected female names ending in 'a' that have been popular since 2015.
5. **Name Popularity Over Time**: Tracked the rise of the name 'Olivia' using cumulative counts.
6. **Most Popular Male Names**: Analyzed the most popular male names for each year.
7. **Top Male Names History**: Determined which male names have been the top name most frequently.
8. **Top Male Names Count**: Counted the number of years each name was the top male name.

## Files

- `datasets/`:

  - `createdb.sql`: SQL script to create the database.
  - `createdblocal.sql`: SQL script for local database setup.
  - `usa_baby_names.csv`: Dataset of American baby names.

- `notebook.ipynb`: Jupyter notebook with SQL queries and analysis.

## Usage

To run the analysis, ensure you have a PostgreSQL database set up with the provided SQL scripts and dataset. Execute the SQL queries in the notebook to explore and visualize the trends in baby names.

## Contact

For questions or further information, please connect with me on LinkedIn.

<a href="https://www.linkedin.com/in/jeanpaulomv/"><img src="https://img.shields.io/badge/jeanpaulomv-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" height="30"></a>
