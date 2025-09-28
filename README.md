# NetFlix_DataAnalysis
Exploratory Data Analysis and insights on Netflix dataset using Python.

This project is a comprehensive exploratory data analysis (EDA) of the Netflix dataset, which contains metadata about movies and TV shows available on the platform.  
The main objective is to uncover insights about Netflix's content library, prepare the dataset for modeling, and explore machine learning approaches such as classification and clustering.

📌 Objectives
- Load and inspect the Netflix dataset
- Clean and preprocess the data (handle missing values, duplicates, inconsistent entries)
- Explore key attributes:
  - Content type (Movie vs. TV Show)
  - Release year trends
  - Country-wise distribution
  - Ratings and genres
  - Duration analysis
- Built a classifier to predict whether a title is a Movie or a TV Show
- Used unsupervised learning (clustering) to group titles by features
- Visualize insights with Seaborn and Matplotlib



📂 Dataset
Source: [Netflix Movies and TV Shows Dataset on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)  
Rows: ~6,200 titles  
Features:
  - `title`, `director`, `cast`, `country`
  - `release_year`, `date_added`, `rating`
  - `duration`, `listed_in` (genres), `description`

---

⚙️ Technologies Used
Python 
Libraries:  
  - `pandas` → data manipulation  
  - `numpy` → numerical operations  
  - `matplotlib`, `seaborn` → visualizations  
  - `scikit-learn` → classification & clustering  

---

🚀 Analysis Highlights
- ✅ Movies dominate the dataset compared to TV Shows  
- ✅ Rapid growth in Netflix content since 2015  
- ✅ USA and India are among the top contributors of content  
- ✅ Common genres: Dramas, Comedies, and Documentaries  
- ✅ Classification model predicts Movie vs TV Show based on features like **duration, rating, and listed genres**  
- ✅ Clustering groups content into meaningful categories for better recommendations  

---

📊 Visualizations
Some of the visualizations included:
- Distribution of Movies vs TV Shows  
- Yearly trend of content release  
- Top 10 countries producing Netflix content  
- Rating distribution (TV-MA, PG, R, etc.)  
- Heatmaps for missing values  


