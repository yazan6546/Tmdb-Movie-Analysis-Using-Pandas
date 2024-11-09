# TMDb Movie Data Analysis

## Table of Contents

- [Project Description](#project-description)
- [Repository Contents](#repository-contents)
- [Running the Code](#running-the-code)
- [Data Cleaning and Normalization](#data-cleaning-and-normalization)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Visualization](#data-visualization)
- [Conclusions](#conclusions)
- [Full Report](#full-report)


## Project Description

This project analyzes movie data from The Movie Database (TMDb) to uncover insights into movie popularity trends and patterns. The primary focus is on exploring the relationship between movie genres and their popularity over time. The project employs data wrangling techniques to clean and prepare the dataset for analysis, followed by exploratory data analysis and visualizations to reveal key trends and patterns.

**Dataset Description:**

The dataset used in this project contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings, revenue, budget, genres, release dates, and more.


## Repository Contents

- `data/tmdb-movies.csv`: The raw dataset containing movie information.
- `Investigate_a_Dataset.ipynb`: Jupyter Notebook containing the data analysis code and visualizations.
- `report/Investigate_a_Dataset.html`: An html version of the original notebook. Included for convenience
- `README.md`: This file, providing an overview of the project.


## Running the Code

1.  Clone this repository to your local machine.
2.  Run this command:
   
    ```
    pip install requirements.txt
    ```
3.  Open the `Investigate_a_Dataset.ipynb` notebook in Google Colab or a Jupyter environment.
4.  Execute the code cells sequentially to perform the analysis and generate visualizations.


## Data Cleaning and Normalization

The data cleaning process involves handling missing values, converting data types, and expanding multi-valued columns to ensure data quality and consistency for analysis.  
Specific steps include:
* Dropping irrelevant columns.
* Filling missing values.
* Transforming data types.
* Handling multi-valued columns.


## Exploratory Data Analysis (EDA)

The exploratory data analysis section investigates the relationship between movie genres and popularity over time. It utilizes descriptive statistics and aggregation techniques to identify trends and patterns in the data.
Specific EDA tasks include:
* Descriptive statistics for the dataset.
* Grouping and aggregating data by genre and release year.
* Identifying the most popular genres for each year.

## Data Visualization

The project utilizes various data visualization techniques to effectively present the findings. Key visualizations include:
* Bar plots showing the popularity of genres over time.
* Heatmaps displaying the average popularity of genres across years.
* Pie chart to illustrate the distribution of Movie Genres.


## Conclusions

The project summarizes the key findings from the analysis, highlighting insights into the popularity of different movie genres across various years. It also discusses potential implications for the movie industry and identifies areas for future research.

## Full Report

For a comprehensive overview of the analysis, including detailed findings and visualizations, please refer to the [full report](https://rawcdn.githack.com/yazan6546/Tmdb-Movie-Analysis-Using-Pandas/2f609fb3707a5586f1524717e42fe958d035ed67/report/Investigate_a_Dataset_final.html) or run the code yourself.
