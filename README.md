# NETFLIX-dataset-analysis
# 🎬 Netflix Data Analysis Project

## 📌 Project Overview
This project analyzes the Netflix dataset to understand patterns and trends in movies and TV shows available on the platform. The objective is to explore content distribution, release trends, and duration characteristics, and to build a simple model to classify content type.

---

## 📊 Dataset Information
- **Dataset Name:** Netflix Shows Dataset  
- **Source:** Kaggle  
- **Rows:** ~8,000+  
- **Columns:** 12  

### Key Columns:
- **show_id:** Unique ID of each title  
- **type:** Movie or TV Show  
- **title:** Name of the content  
- **director:** Director of the content  
- **cast:** Actors involved  
- **country:** Country of production  
- **release_year:** Year of release  
- **rating:** Content rating (e.g., PG, TV-MA)  
- **duration:** Duration in minutes or seasons  
- **listed_in:** Genre/category  

---

## 🛠 Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## 🔍 Project Workflow

### 1. Data Cleaning
- Handled missing values using forward fill  
- Removed duplicate rows  
- Cleaned column names for consistency  
- Converted duration into numeric format  

---

### 2. Statistical Analysis
- Calculated mean, median, and mode  
- Computed standard deviation and variance  
- Calculated range and mid-range  

---

### 3. Data Visualization
- Histogram of release year distribution  
- Countplot of content type (Movies vs TV Shows)  
- Boxplot of duration  
- Correlation heatmap  

---

### 4. Predictive Modeling
- Encoded categorical variables  
- Split dataset into training and testing sets (80:20)  
- Applied Logistic Regression  
- Evaluated model using accuracy score  

---

## 📈 Key Insights
- Netflix has more movies than TV shows  
- Most content is released after the year 2000  
- Duration varies widely, with some extreme outliers  

---

## 💡 Recommendations
- Netflix should continue focusing on modern content  
- Increasing high-quality TV shows may improve engagement  

---

## 📂 Repository Contents
- `Netflix Shows.csv`  
- `netflix_analysis.ipynb`  
- `README.md`  

---

## 🔗 Author
**Vedika Thombare**  
B.Tech CSE (AI & DS)
