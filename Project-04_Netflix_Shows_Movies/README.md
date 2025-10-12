# 🎬 Netflix Shows and Movies

This project performs Exploratory Data Analysis (EDA) on a Netflix dataset to uncover insights into the **content library, genre trends, release patterns**, and **platform diversity**.
The dataset contains detailed metadata about Netflix shows and movies, including titles, cast, directors, release year, genres, and countries of origin.

---

## 📌 Objective

- Perform data cleaning and preprocessing.
- Explore content distribution across genres, countries, and years.
- Identify missing values and handle them appropriately.
- Analyze trends in content release over time.
- Compare shows vs movies in terms of volume, ratings, and duration.
- Create visualizations to identify viewer and production trends.

---

## 📂 Dataset Source

- **Name**: netflix_titles.csv
- **Source**: Publicly available dataset from Kaggle – Netflix Movies and TV Shows
- **Rows**: ~8,800
- **Columns**: 12

**Features**:
- show_id
- type (Movie / TV Show)
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in (Genres)
- description

---

## 📁 Folder Structure

```text
Project-04_Netflix_Shows_Movies/
│
├── diabetes-eda/
│   ├── data/
│   │   ├── raw/            # Original dataset
│   │   ├── processed/      # Cleaned dataset
│   │
│   ├── notebooks/
│   │   ├── netflix_eda.ipynb
│   │
│   ├── README.md           # Project documentation
│
└── requirements.txt
```

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Google Colab

---

## 📈 Key Visualizations

- **Content Type Distribution** – Count plot showing Movies vs TV Shows.
- **Top Genres** – Bar plot of the most common categories listed.
- **Content Over Time** – Line plot of number of releases per year.
- **Country-wise Content** – Bar chart of top-producing countries.
- **Ratings Distribution** – Count plot of rating categories (e.g., TV-MA, PG, R).
- **Word Cloud** – Visualization of the most frequent words in show and movie descriptions.

---

## 🔍 Key Insights

- Netflix’s content library is dominated by movies, though TV shows have grown steadily since 2015.
- The United States and India are top contributors to Netflix’s content catalog.
- Dramas and comedies are the most popular genres across both shows and movies.
- Content releases peaked around 2018–2020, reflecting Netflix’s aggressive content expansion.
- Word Cloud analysis highlights recurring themes like love, life, family, and crime.

---
