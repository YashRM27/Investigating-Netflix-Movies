# Investigating-Netflix-Movies

This project is part of a data analysis exercise on the `netflix_data.csv` dataset.  
The focus is on **movies released during the 1990s decade (1990–1999)**.

## 📌 Objectives
1. Filter Netflix movies from **1990–1999**.
2. Find the **most frequent movie duration** in that decade.
3. Count the number of **short Action movies** (movies with duration < 90 minutes) released in the 1990s.

## 📂 Dataset
- **File:** `netflix_data.csv`
- **Columns used:**
  - `title` – Movie name
  - `date_added` – Date the movie was added to Netflix
  - `release_year` – Release year of the movie
  - `duration` – Duration in minutes
  - `genre` – Movie category

## 🔍 Methodology
1. Convert `date_added` to a proper datetime format.
2. Filter the dataset for movies released between **1990 and 1999**.
3. Compute the **median/most frequent duration** of movies in the 1990s.
4. Identify **short Action movies (< 90 mins)** and count them.

## ✅ Results
- **Most frequent movie duration (1990s):** 108 minutes  
- **Short Action movies (1990s):** 7


## 📊 Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

