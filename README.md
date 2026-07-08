# 📺 Netflix Data Analysis (EDA)

## Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Titles dataset using Python. The aim is to clean the data, explore patterns, and visualize trends in Netflix's movies and TV shows.

## Dataset

* **Source:** Kaggle Netflix Titles Dataset
* **Records:** Approximately 8,800+ titles
* **Features:** Title, Type, Director, Cast, Country, Release Year, Rating, Duration, Date Added, Genre, Description, and more.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Workflow

* Imported the dataset
* Explored the dataset structure
* Cleaned missing and inconsistent values
* Checked data types
* Performed univariate and bivariate analysis
* Created visualizations to identify trends and patterns
* Summarized key insights

## Visualizations

The analysis includes charts such as:

* Movies vs TV Shows
* Top 10 Content Producing Countries
* Content Ratings Distribution
* Titles Released by Year
* Most Common Genres
* Content Added Over Time

## Key Insights

* Movies make up a larger portion of Netflix's catalog than TV Shows.
* A few countries contribute a significant share of Netflix content.
* Most titles were added to Netflix in recent years.
* Certain content ratings appear much more frequently than others.
* Netflix offers content across a wide variety of genres and release years.

## Repository Structure

```text
Netflix-EDA/
│── Netflix_EDA.ipynb
│── netflix_titles.csv
│── README.md
│── images/
```

## How to Run

1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells to reproduce the analysis.

## Learning Outcomes

Through this project, I practiced:

* Data cleaning
* Handling missing values
* Exploratory Data Analysis (EDA)
* Data visualization
* Drawing insights from real-world data using Python
