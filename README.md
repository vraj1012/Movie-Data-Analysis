# Netflix Movie Data Analysis

## Project Overview
This project analyzes Netflix movie data to extract insights into movie trends, ratings, and popularity. The dataset consists of **9,827 rows and 9 columns**, including attributes like release date, title, genres, vote count, and popularity.

## Features
- **Data Cleaning and Preprocessing**:
  - Converted `Release_Date` to datetime format.
  - Removed whitespaces and unnecessary characters from `Genre`.
  - Dropped unneeded columns (`Overview`, `Original_Language`, `Poster_Url`).
  - Categorized `Vote_Average` for better classification.
  - Transformed `Genre` into **First Normal Form (1NF)**.

- **Exploratory Data Analysis (EDA)**:
  - Identified trends in movie ratings and popularity.
  - Analyzed distributions of vote counts and ratings.
  - Explored genre-wise trends and popularity metrics.

- **Visualizations**:
  - Bar charts and histograms for rating distributions.
  - Popularity trends over time.
  - Genre-wise analysis of movie counts and ratings.

## Dataset
The dataset contains the following columns:
- **Release_Date**: The date when the movie was released.
- **Title**: Name of the movie.
- **Overview**: Brief description of the movie.
- **Popularity**: A numerical measure of movie popularity.
- **Vote_Count**: The total number of votes received.
- **Vote_Average**: The average rating of the movie.
- **Original_Language**: The language in which the movie was originally released.
- **Genre**: The categories associated with the movie.
- **Poster_Url**: A link to the movie poster.

## Technologies Used
- **Python**: Data processing and analysis.
- **Pandas**: Data wrangling and manipulation.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: Code execution and analysis.

## Results & Insights
- Movies with higher vote counts tend to have higher popularity scores.
- Certain genres (e.g., Action, Adventure) dominate in popularity.
- Ratings are normally distributed, with most movies scoring between 5 and 8.
- Movie popularity has increased significantly in recent years.
