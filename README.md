## 🍽️ Restaurant Recommendation System

A data-driven Restaurant Recommendation System built using Python, Apache Spark, and R, leveraging Zomato’s restaurant dataset to recommend similar restaurants based on reviews, cuisines, and ratings.

### 🔗 Dataset: https://drive.google.com/file/d/16btZdVpeZcn5TNT3SU0bhaKOso4s_5xy/view?usp=sharing

### 🧠 Project Overview

The project explores restaurant data to:

* Analyze and visualize restaurant trends.

* Clean, preprocess, and transform large datasets using PySpark.

* Implement a content-based recommendation system.

* Recreate the model workflow using R for cross-language validation.

### ⚙️ Technologies Used

* Languages: Python, R.

* Libraries: Pandas, NumPy, Seaborn, Matplotlib, PySpark, Scikit-learn, TM, Proxy.

* Tech Stack: Apache Spark, Google Colab, RStudio.

* Machine Learning Concepts: TF-IDF, Cosine Similarity, Text Cleaning, Stopword Removal.


### 📊 Methodology

🔹 Data Collection & Cleaning

* Loaded dataset from Zomato using Google Drive.

* Removed duplicates, missing values, and unnecessary columns.

* Cleaned text data (reviews) by removing URLs, punctuation, and stopwords.

🔹 Data Analysis & Visualization

* Visualized restaurant statistics — location, rating distribution, service types, costs, and online booking trends.

* Identified correlations among restaurant features.

🔹 Model Development & Recommendation

* Computed TF-IDF vectors for restaurant reviews.

* Calculated Cosine Similarity to recommend restaurants with similar reviews and cuisines.

* Built scalable pipeline using PySpark for large data processing.

🔹 Cross-Implementation in R

* Replicated the process using R (tm & proxy packages) for reproducibility.

* Used TF-IDF and cosine similarity to generate top-10 restaurant recommendations.

### 📈 Sample Results

| 🍴 **Model/Approach**      | ⚡ **Framework**             | 🎯 **Goal**                   | 📊 **Result**                                  |
| :------------------------- | :-------------------------- | :---------------------------- | :--------------------------------------------- |
| TF-IDF + Cosine Similarity | PySpark                     | Recommend similar restaurants | Successful recommendations with top-10 matches |
| Text Cleaning + TF-IDF     | R                           | Replicate results in R        | Consistent output and similarity ranking       |
| Data Visualization         | Python (Matplotlib/Seaborn) | Explore restaurant trends     | Insightful graphs and heatmaps                 |

### 📍 Key Visualizations

* Restaurant distribution by city.

* Online order vs rating comparison.

* Cost vs rating trends.

* Most popular restaurant chains.

### 🧩 Future Enhancements

* Integrate collaborative filtering for hybrid recommendations.

* Build a web dashboard (Streamlit or Shiny).

* Add sentiment analysis on reviews.
