# Etsy-Art_Analysis

## Project Summary
This repository contains my analysis of Etsy listings, focusing on structure and keyword attributes of Etsy listings. The data was obtained via the Etsy API and is stored in an SQLite database (`etsy_data.db`). The goal of this analysis is to elucidate best practices for listing art-related items on Etsy to generate viewing traffic to art related Etsy listings. 
## Database Structure
The database consists of three datasets:

1. **Review Data**: Contains customer reviews for various listings, allowing for sentiment analysis.
2. **Shop Data**: Includes information about shops, such as transaction counts and shop IDs.
3. **Listings Data**: Features details of each listing, including titles, prices, and listing types.

## How to Use the Database
To access the SQLite database:

1. **Download the `etsy_data.db` file** from this repository.
2. **Open it using any SQLite client or library**, such as SQLite Studio, DB Browser for SQLite, or via Python using the `sqlite3` module.
3. SQL queries used to extract and analyze data are embedded within the **Jupyter Notebooks** in this repository.

## Notebooks
The Jupyter Notebooks contain detailed analyses, visualizations, and SQL queries used throughout the project. Please refer to these notebooks for insights and methodologies.

## Results
The **Results** folder contains a **PDF version** of the Canva Slides presentation, showcasing key visualizations and summarizing best practices for successful Etsy listings.

## Repository Structure
The repository is organized into the following main folders:

1. **Data**: Contains the SQLite database (`etsy_data.db`).
2. **Notebooks**: Jupyter notebooks used for analysis, including SQL queries and Python visualizations.
3. **Results**: The Google Slides presentation PDF showcasing the project's key findings and recommendations.

## Links
- Project summary and insights on my website: [Link to blog post]([https://melissafisheranalytics.com/blogs/analytics-portfolio/blog](https://melissafisheranalytics.com/collections/all))
