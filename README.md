# YouTube-ETL
YouTube Trending Videos ETL Pipeline

# Project Overview
This project focuses on building an ETL (Extract, Transform, Load) pipeline to fetch and analyze trending YouTube videos using the YouTube Data API. The extracted data is processed and stored in a structured format for further analysis.

# Tools & Technologies
1. Python (Requests, Pandas)
2. YouTube Data API v3 (for fetching trending videos)
3. Google Colab (for execution and testing)

# Workflow
1. Extract: Fetch trending YouTube videos using API calls.
2. Transform: Clean and structure the data (remove missing values, convert data types).
3. Load: Store the processed data into a Pandas DataFrame for analysis.

# Key Features

1. Fetches real-time trending videos from YouTube.
2. Allows users to specify region code (e.g., US, IN, GB).
3. Stores video details: title, channel, views, likes, and comments.
4. Handles API errors and invalid inputs gracefully.

# Files in This Repository

1. YouTube_ETL.ipynb → Google Colab notebook for ETL pipeline.
2. README.md → Project documentation.

# How to Use

1. Open Colab Notebook (YouTube_ETL.ipynb).
2. Run the script and enter the region code and number of results.
3. View the structured dataset containing trending video details.

🔗 Colab Notebook Link
https://colab.research.google.com/drive/1-L-8JQFPc309eioCi9Ta-J0kiFbp0O2T?usp=sharing

🔗 YouTube API Documentation
https://developers.google.com/youtube/v3/getting-started


