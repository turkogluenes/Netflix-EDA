#  Netflix Dataset Exploratory Data Analysis

This project performs an exploratory data analysis (EDA) on Netflix’s public catalog dataset. The goal is to uncover insights about content types, ratings, release trends, production countries, and durations through data cleaning, transformation, and visualization.

##  Dataset
- Source: [Kaggle - Netflix Titles](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- 8,000+ rows of content including movies and TV shows.
- Features: type, title, cast, country, date_added, release_year, rating, duration, and more.

##  Main Tasks
- Data cleaning & missing value handling
- Feature extraction (e.g., year added)
- Visual analysis of:
  - Content types
  - Ratings
  - Release trends
  - Top contributing countries
  - Movie durations

##  Key Insights
- Movies dominate the catalog.
- Most content is rated for mature audiences.
- Release counts peaked in 2020.
- U.S., India, and UK are top contributors.
- Standard-length films (~90 mins) are most common.

##  Files
- `netflix_eda.ipynb`: Jupyter notebook with full analysis
- `README.md`: This file

##  Visuals
> You can see visualizations inside the notebook file.

##  Future Improvements
- Add time series analysis on date_added
- Analyze genres (`listed_in` column)

