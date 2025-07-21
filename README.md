# Netflix_Analysis
# 🎮 Netflix Content Analysis

Exploratory Data Analysis of 6,000+ Netflix shows and movies using Python.

## 🌟 Objective

The goal of this project is to analyze Netflix's content library to understand trends in content type, genre popularity, release years, and country-wise distribution. This analysis helps identify how Netflix has evolved over the years and what kind of content it invests in globally.

## 📦 Dataset

* **Source:** [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* Contains 6,000+ Netflix shows and movies with fields like title, cast, director, country, date added, release year, genre, and description.

## 📊 Steps Performed

### ✅ 1. Data Loading & Initial Exploration

* Loaded the dataset using Pandas
* Explored column types and sample rows

### ✅ 2. Data Cleaning

* Filled missing values in `cast` and `director`
* Dropped rows with null `date_added` or `country`
* Converted `date_added` to datetime
* Created new columns: `year_added`, `month_added`

### ✅ 3. Feature Analysis & Visualizations

#### 🎮 Content Type Distribution

* Bar plot showing more Movies than TV Shows

#### 📅 Content Added Over Years

* Histogram showing growth in content, especially post-2015

#### 🌍 Top 10 Countries by Content

* Horizontal bar chart of most contributing countries
* US leads, followed by India and the UK

#### 🎭 Top 10 Genres

* Extracted genres from `listed_in` column
* Counted and visualized most common genres

#### ☁️ WordCloud from Descriptions

* Generated WordCloud using `description` column
* Shows common themes like love, family, crime, drama

## 📍 Key Insights

* Netflix's content growth accelerated after 2015
* The platform remains movie-dominant but TV Shows are growing
* Drama, Documentary, and Comedy are leading genres
* Most content is produced in the US, but Indian and British content is also significant

## 📖 Tools & Libraries Used

* Python, Pandas, Matplotlib, Seaborn
* WordCloud
* Google Colab



## 🚀 How to Run

1. Open `Netflix_Analysis.ipynb` in Google Colab
2. Upload the `netflix_titles.csv` file
3. Run the cells and explore visual insights

## 📊 Future Work

* Add genre-wise trend over years
* Build recommendation system based on content similarity
* Deploy interactive dashboard using Streamlit

## 🔖 Author

Nalla Venkata Sai Krishna Anjana Jyothi
