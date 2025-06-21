# Spotify-Music-Data-Analysis
This project aims to explore and analyze a dataset of songs available on Spotify. The objective is to derive insights about trends in music features such as popularity, danceability, energy, and more across different albums, years, and languages.

## 📂 Dataset Information
- **Source**: [Mention the source – e.g., Kaggle, Spotify API, or local CSV]
- **Size**: (e.g., 32,000+ songs)
- **Features Included**:
  - `track_name`, `artist`, `album_name`
  - `year`, `language`, `popularity`
  - `danceability`, `energy`, `duration_ms`

---

## 🛠️ Tools & Libraries
- Python
- pandas, matplotlib
- Google Colab

---

## 🧹 Data Cleaning Steps
- Removed entries with `album_name` as "unknown"
- Filled or dropped missing values where necessary
- Standardized column names and string formats
- Converted `duration_ms` to minutes for readability

---

## 📊 Exploratory Data Analysis (EDA)

### 🔸 Most Danceable Albums
- Top 10 albums with the highest total danceability score
- Grouped by `year` and `album_name`

### 🔸 Popularity by Language
- Bar chart showing average popularity of songs grouped by `language`
---

## 📈 Key Insights
- Certain albums from recent years dominate danceability scores.
- English and Hindi songs show higher average popularity.
- Songs are becoming more energetic and upbeat over the years.

---

## ⚠️ Challenges Faced
- Unclear or missing language labels
- Outliers affecting distribution plots
- Aggregation logic for album-level insights

---

## ✅ Conclusion
The project successfully revealed musical trends and user preferences using Spotify data. These insights could help artists, listeners, or platforms understand evolving tastes in music.

---

## 🚀 Future Enhancements
- Sentiment analysis of lyrics using NLP
- Clustering similar songs using K-Means
- Building a content-based recommendation system

---

## 📎 Project Status
`Completed` - All visualizations and inferences documented.
