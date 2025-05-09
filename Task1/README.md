# Netflix Data Cleaning and Exploration

This repository contains a data cleaning and preprocessing project based on the Netflix Movies and TV Shows dataset. It was completed as part of my internship, with the goal of preparing the dataset for exploratory data analysis and downstream analytics.

# Project Objective

The objective of this project was to:
- Load and inspect the raw Netflix dataset
- Handle missing values and inconsistent formats
- Convert relevant columns to appropriate data types
- Ensure the dataset is analysis-ready for further insights or machine learning applications

# Dataset

The dataset used in this project is:
- **Source**: [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File**: `netflix_titles.csv`
- Contains metadata for Netflix content including title, director, cast, country, date added, release year, rating, duration, and description.

# Cleaning Steps Performed

- Removed leading/trailing whitespace in column names
- Converted `date_added` to datetime format
- Replaced missing values with placeholders in fields like `director`, `cast`, `country`, and `rating`
- Removed duplicate entries
- Exported the cleaned dataset to `netflix_titles_cleaned.xlsx`

# Tools Used

- Python 🐍
- Pandas 📊
- Jupyter Notebook 📒

# Files Included

- `Netflix_Movies_and_Shows_Cleaning.ipynb` – The main notebook with all data cleaning steps
- `netflix_titles_cleaned.xlsx` – Cleaned version of the dataset (optional output)
- `README.md` – Project overview and documentation

# Acknowledgments

- Project completed as part of my internship, focusing on real-world data cleaning workflows.
---
Feel free to fork or star this repo if you find it useful!
