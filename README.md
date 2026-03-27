# Mars Web Scraping & Data Analysis

## Overview
This project focuses on web scraping and data analysis using Python. Data is collected from Mars-related wensites through automated browsing and HTML parsing, then structured, analyzed, and visualized to uncover inisghts about Martian weather and news trends.

The project demonstrates end-to-end handling, including data collection, transformation, analysis, and visualization.

## Project Deliverables
**Part 1: Mars News Scraping**
* Used automated browsing to visit a Mars news website
* Parsed HTML using Beautiful Soup
* Extracted
  * News titles
  * Preview text
* Stored results as:
  * List of dictionaries (title, preview)
 
**Part 2: Mars Weather Analysis**
* Scraped Mars temperature data from an HTML table
* Parsed data using Beautiful Soup
* Converted data in a Pandas DataFrame

**Data Processing**
* Assigned appropriate data types (datetime, int, float)
* Structured columns:
  * `id`, `terrestrial_date`, `sol`, `ls`, `month`, `min_temp`, `pressure`

**Analysis Performed**
* Total number of Martian months
* Total number of Martian days (sols) in dataset
* Coldest and warmest months (based on average minimum temperature)
* Months with lowest and highest atmospheric pressure
* Estimated length of a Martian year (in Earth days)

**Visualizations**
* Bar chart: average minimum temperature by month
* Bar chart: average atmospheric pressure by month
* Line plot: daily minimum temperatures over time

**Dataset was exported to CSV**
