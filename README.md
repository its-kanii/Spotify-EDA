# 🎧 Spotify Tracks EDA Project

This project is part of my **100 Days of Data Science** learning journey. On **Day 2**, I explored the Spotify Tracks Dataset using Python and performed **Exploratory Data Analysis (EDA)** to uncover patterns in music data like tempo, popularity, release trends, and more.

## 📌 Objective

To explore patterns in Spotify music tracks using EDA techniques and visualize key relationships in the data such as:

- Tempo vs Popularity
- Top genres
- Track release trends

## 📂 Dataset

- **Name**: Spotify Tracks Dataset
- **Source**: [Kaggle or source link here if applicable]
- Contains information about various Spotify tracks including:
  - `track_name`, `artist`, `popularity`, `tempo`, `release_date`, `genre`, etc.

## 🛠️ Tools & Libraries Used

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 EDA Steps

1. **Load Dataset**
   - Using `pandas.read_csv()` to read and inspect the dataset.

2. **Basic Analysis**
   - Checked dataset shape, data types, and null values.
   - Used `.value_counts()` for categorical columns like genres.

3. **Data Cleaning**
   - Removed duplicates
   - Handled null values
   - Converted data types for better analysis

4. **Visualization**
   - Scatter plot: `tempo` vs `popularity`
   - Bar plots: top genres or release year distribution
   - Line plot: release trends over time

5. **Learnings**
   - Faced multiple errors while plotting:
     - Glyph issues
     - Layout warnings
   - Learned how to fix font issues, use `tight_layout`, and improve visuals.
   - Realized that **errors help you grow**!

## 💡 Key Insights

- Songs with moderate tempo often have higher popularity.
- Certain genres dominate the dataset.
- There’s a noticeable trend in track releases over time.

## 🚀 What's Next?

- Improve plots using interactive libraries like Plotly or Altair
- Try clustering tracks based on audio features
- Compare Spotify data across different countries or time periods

## 📎 Links

- 📘 **Blog Post**: [Coming soon]
- 💻 **GitHub Notebook**: [Coming soon]

## 📅 Part of My Series

This is **Day 2** of my `#MyDataScienceDiary` series. Stay tuned for **Day 3**! 🚀

---

### 📢 Connect with me

If you're also learning Data Science or working with Spotify data, feel free to connect and share your journey!

