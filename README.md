# WiDS_5.0_Movie_Recommendation_System
A content based movie-recommendation system that suggests similar movies based on metadata like genre, cast, keywords, plot overview etc.
This project focuses on building a Content-Based Movie Recommendation System that suggests movies similar to a selected movie by analyzing movie metadata such as genre, cast, crew, keywords, and plot overview.
The system identifies similarities between movies based on their content features using basic NLP and vectorization techniques.

## What I Learned Through This Project

### Week 1: Foundations of Python & Data Science

The first week of the project was dedicated to building a strong foundation in Python.  
The focus was on understanding core programming concepts that are essential for data analysis and machine learning.

### Week 2: Learning essential Python libraries

**This includes:**
- **NumPy** for numerical computations
- Using **Pandas** for data manipulation and analysis
- Data Visualisation by **Matplotlib**
- Exploratory data analysis of movie datasets  
- Classification of movies based on their genres  


### Week 3: NLP & Recommendation System Concepts

**This includes:**
- Understanding and implementing **Count Vectorizer**
- Measuring similarity using **Cosine Similarity**
- Merging multiple datasets into a **master dataset**
- Text preprocessing techniques in **NLP**, including:
  - Tokenization
  - Stemming
  - Lemmatization
- Extracting meaningful features from text data such as plot summaries, keywords, cast, and crew.

### In the following weeks, wemoved on to building the movie-recommendation system
# 🎬 Movie Recommendation System  

A simple **content-based movie recommender** built using Python that suggests movies similar to a given title based on metadata.

---

##  Features
-  Data analysis with **Pandas & NumPy**
-  Text preprocessing using **NLTK**
- Feature engineering with a custom *soup*
- Vectorization via **CountVectorizer**
-  Similarity calculation using **Cosine Similarity**

---

##  Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib  
- NLTK  
- Scikit-learn  

---

##  Dataset
Multiple movie-related CSV files were merged and cleaned to form a **master dataset of the top 2500 movies**.

---

##  How It Works
1. Preprocess movie metadata (cast, crew, keywords)
2. Convert text to numerical vectors
3. Compute cosine similarity
4. Recommend the most similar movies 🎥

---

##  Output
Given a movie title, the system returns:
- 🎞 Recommended movies  
- 🎬 Director  
- 📅 Release date  

---

##  Conclusion
This project was developed as part of **Winter in Data Science (WiDS) 5.0**, offering hands-on experience with **data science, NLP, and recommender systems**.


