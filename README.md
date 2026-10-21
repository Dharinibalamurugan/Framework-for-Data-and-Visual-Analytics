# Framework-for-Data-and-Visual-Analytics

Netflix Content & Viewing Trend Analysis
Exploratory data analysis of the Netflix catalog (6,234 titles) using Python, Pandas, Matplotlib and Seaborn.
Name: Dharini
Register No.: 241501044
Department: Artificial Intelligence and Machine Learning
Institution: Rajalakshmi Engineering College, Chennai
Objective
Understand how the Netflix catalog is composed and how it has grown: content types, countries, genres, ratings, durations and addition trends.
Dataset
Netflix Titles (netflix_titles.csv), 6,234 rows and 12 columns: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description.
Approach
Inspect: shape, data types, missing values, duplicates
Clean: strip whitespace and parse date_added, fill missing director, cast, country and rating with "Unknown", extract year and month added, convert duration to numbers
Explore: type split, titles added per year and month, release years, top countries and genres, ratings, movie duration, TV seasons, India-specific view
Statistics: mean, median, mode, range, variance, standard deviation
Key Findings
4,265 movies vs 1,969 TV shows (about 68% movies)
Top producers: United States (2,609), India (838), United Kingdom (601)
Top genres: International Movies, Dramas, Comedies
Most common rating: TV-MA (2,027), then TV-14 (1,698)
Additions peaked in 2019 (2,349 titles); the 2020 count is partial
Average movie runs about 99 minutes (median 98)
About 67% of TV shows have a single season
Repository Structure
├── Netflix_Content_Viewing_Trend_Analysis.ipynb   # implementation
├── netflix_titles.csv                             # dataset
├── Report.pdf                                     # project report
└── README.md
How to Run
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Netflix_Content_Viewing_Trend_Analysis.ipynb
Keep netflix_titles.csv in the same folder as the notebook. In Google Colab, upload the CSV and run all cells.
Future Scope
Recommendation system based on genre and description
Genre prediction with machine learning
Sentiment analysis on descriptions
Interactive dashboard with Plotly or Power BI