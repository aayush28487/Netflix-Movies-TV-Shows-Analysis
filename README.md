# 🎬 Netflix Movies & TV Shows Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python.

The objective is to understand patterns in Netflix's content based on content type, release year, countries, genres, ratings, movie duration, and other attributes.

The project focuses on **data cleaning, data exploration, visualization, and extracting meaningful insights** from a real-world dataset.

---

## 🎯 Objectives

* Understand and explore the Netflix dataset
* Identify and handle missing values
* Check and handle duplicate records
* Analyze Movies vs TV Shows
* Analyze titles by original release year
* Analyze content added to Netflix by year
* Identify the countries most represented in the dataset
* Analyze popular genres and ratings
* Analyze movie durations
* Explore Indian content
* Visualize patterns using Matplotlib and Seaborn
* Extract meaningful insights from the data

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* **Jupyter Notebook**

---

## 📂 Dataset

The dataset contains information about Netflix Movies and TV Shows, including:

* Show ID
* Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genres
* Description

The dataset contains **8,807 records and 12 original columns**. An additional `year_added` column was created during the data-cleaning process.

---

## 🔍 Data Cleaning

The following preprocessing steps were performed:

* Checked the structure and data types of the dataset
* Checked for missing values
* Checked for duplicate records
* Converted `date_added` into a datetime format
* Created a `year_added` column from `date_added`
* Handled missing categorical values
* Extracted numerical movie duration from the `duration` column
* Separated Movies and TV Shows for specific analyses
* Split multi-value country and genre fields for individual analysis

---

## 📊 Exploratory Data Analysis

The project analyzes:

### 1. Movies vs TV Shows

The dataset contains:

* **6,131 Movies**
* **2,676 TV Shows**

Movies represent approximately **69.6%** of the dataset, while TV Shows represent approximately **30.4%**.

### 2. Titles by Release Year

The highest number of titles in the dataset have an original release year of **2018**, with **1,094 titles**, followed by:

* 2019 — 1,013
* 2020 — 953
* 2017 — 939
* 2016 — 796

### 3. Content Added to Netflix

The highest number of titles were added to Netflix in the dataset during:

* **2020 — 1,807 titles**
* **2019 — 1,786 titles**
* **2021 — 1,492 titles**
* **2018 — 1,468 titles**
* **2017 — 1,029 titles**

### 4. Country Analysis

The country analysis identifies the countries with the highest number of Netflix titles.

The **United States** is the most represented country in the dataset, followed by **India** and the **United Kingdom**.

### 5. Genre Analysis

The project analyzes the most frequently occurring genres by splitting titles that contain multiple genre categories.

### 6. Rating Analysis

The distribution of Netflix titles across different content ratings is analyzed using Pandas and Seaborn.

### 7. Movie Duration Analysis

Movie duration values such as `"90 min"` and `"120 min"` were converted into numerical values to analyze:

* Average duration
* Median duration
* Minimum duration
* Maximum duration
* Distribution of movie lengths

### 8. Indian Content Analysis 🇮🇳

The project also performs a focused analysis of Netflix titles associated with India, including:

* Movies vs TV Shows
* Release years
* Genres
* Other content characteristics

---

## 📈 Visualizations

The project uses **Matplotlib and Seaborn** to create visualizations such as:

* Movies vs TV Shows
* Titles by Release Year
* Content Added by Year
* Top Countries
* Top Genres
* Content Ratings
* Movie Duration Distribution
* Correlation Heatmap

---

## 💡 Key Insights

* Movies account for approximately **69.6%** of the titles in the dataset, while TV Shows account for approximately **30.4%**.
* **2018** has the highest number of titles by original release year, with **1,094 titles**.
* **2020** has the highest number of titles added to Netflix in the dataset, with **1,807 titles**.
* The **United States** is the most represented country in the dataset, followed by **India**.
* Netflix's catalog contains a wide variety of genres and content ratings.
* The dataset contains both recent and older titles, providing an opportunity to analyze changes in Netflix's catalog over time.

---

## ⚠️ Limitations

* The dataset represents a snapshot and may not reflect Netflix's current catalog.
* Some records contain missing date information.
* Some titles contain multiple countries and genres.
* The dataset does not contain information about viewing hours, revenue, or audience popularity.
* The analysis identifies patterns and relationships in the dataset but does not establish causal relationships.

---

## 📓 Project Notebook

The complete analysis is available in:

**`Netflix_Movies_TV_Shows_Analysis.ipynb`**

The notebook contains the complete Python code, data-cleaning steps, analysis, visualizations, and findings.

---

## 🚀 Skills Demonstrated

This project demonstrates practical experience with:

* Python programming
* NumPy
* Pandas
* Data cleaning
* Exploratory Data Analysis (EDA)
* Data transformation
* Data visualization
* Matplotlib
* Seaborn
* Statistical exploration
* Extracting insights from real-world datasets

---

## 📌 Conclusion

This project provided practical experience in transforming a raw dataset into meaningful information through data cleaning, exploratory analysis, and visualization.

The analysis explored Netflix content across multiple dimensions including content type, release year, countries, genres, ratings, movie duration, and Indian content.

Overall, the project demonstrates how Python-based data analysis can be used to understand patterns and extract useful insights from a real-world dataset.
