# netflix-eda-project
# 📊 Netflix Data Analysis & Machine Learning Project

This project performs Exploratory Data Analysis (EDA), Natural Language Processing (NLP), and basic Machine Learning (ML) on a dataset of Netflix TV shows and movies.

---

## 📁 Dataset

**Source**: `Netflix TV Shows and Movies.csv`  
Contains metadata such as:
- Title, Type (Movie/Show), Release Year
- Age Certification, Runtime
- Description, IMDb Score and Votes

---

## 🔍 Project Objectives

- Clean and preprocess the dataset
- Analyze trends in release years, types, certifications
- Perform text analysis on content descriptions
- Build predictive models and content clusters
- Visualize insights using plots

---

## 📌 Key Features

### 1️⃣ Exploratory Data Analysis (EDA)
- Distribution of movies vs shows
- Release trend over the years
- Runtime and rating patterns
- IMDb score analysis

### 2️⃣ Data Cleaning
- Handled null values in `description`, `age_certification`
- Removed duplicates and normalized text fields

### 3️⃣ Feature Engineering
- Created `content_age` and `is_old_classic` columns
- Extracted release trends and certification categories

### 4️⃣ NLP (Text Mining)
- TF-IDF vectorization on content descriptions
- KMeans clustering to group similar titles
- WordCloud visualization (optional)

### 5️⃣ Machine Learning
- Random Forest classifier to predict content `type`
- Feature input: IMDb score, runtime, content age

### 6️⃣ Visualization
- Used Seaborn & Matplotlib for trend analysis
- Optional: Plotly or Tableau for dashboards

---

## 🛠️ Tools & Libraries

- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn** (TF-IDF, KMeans, RandomForest)
- **Google Colab** / Jupyter Notebook

---

## 📂 Files in this Repository

| File Name               | Description                                      |
|------------------------|--------------------------------------------------|
| `Netflix_EDA.ipynb`    | Full notebook with analysis, charts, and ML      |
| `netflix_cleaned.csv`  | Cleaned dataset after preprocessing (optional)   |
| `README.md`            | Project overview (this file)                     |

---

## 📈 Sample Insights

- 📅 Most Netflix content was released post-2010
- 🎬 Movies outnumber shows by ~2:1
- ⭐️ Top-rated titles (IMDb 8+) are rare
- 🧠 Description-based clusters reveal genre similarities

---

## 🚀 How to Run

1. Open the notebook: `Netflix_EDA.ipynb`
2. Run each cell in order
3. Optionally: visualize results in Tableau or export `.csv`

---

## 🧠 Skills Gained

✅ Data wrangling and exploration  
✅ Feature engineering and analysis  
✅ Text vectorization (TF-IDF)  
✅ Clustering and classification  
✅ Dashboard storytelling  

---

## 🌐 Author

**Priyanka Gupta**  
_Data Science & Machine Learning Student_  
📫 [LinkedIn](www.linkedin.com/in/priyanka-gupta-063b30292) | [GitHub](https://github.com/)

---

⭐️ If you liked this project, give it a star on GitHub!

