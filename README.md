# 🎬 Movie Industry Analysis

## 📌 Overview
This project aims to analyze the **factors influencing the commercial success of movies** using a dataset from [Kaggle's Movie Industry dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies).  
By examining variables such as **budget, vote count, score, runtime, genre, and rating**, our goal was to identify what makes a movie successful both critically and financially.

---

## 👥 Team Members
- WonJune Lee  
- Geunwoo Park  
- Hyeyeon Kweon  
- Juheon Kim  
- Jungbin Eom  
- Soobin Jang  

---

## 🎯 Research Question
> **"What are the key factors that contribute to a film's success in the movie industry?"**

---

## 📊 Dataset
- Source: [Kaggle - Movie Industry Dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies)
- Records: 7,668 movies
- Variables: `title`, `genre`, `year`, `score`, `votes`, `budget`, `gross`, `director`, `star`, etc.
- Time Span: 1980–2020 (approximately 40 years)

---

## 🔍 Key Analyses

### 1. **Exploratory Data Analysis (EDA)**
- **Budget & Gross Revenue Distribution** (Boxplots)
- **Rating Popularity Distribution**
- **Top Genres by Popularity**
- **Top Directors and Actors by Movie Count**
- **Score Distribution and Top-rated Movies**
- **Yearly Movie Counts & Country-wise Distribution**

### 2. **Correlation & Regression**
- **Linear Regression Models**
  - Budget vs. Gross → *R² = 0.6165*
  - Votes vs. Gross → *R² = 0.4342*
  - Score vs. Gross → *R² = 0.0409*
  - Runtime vs. Gross → *R² = 0.0638*
- **Multiple Regression**
  - Predictors: Budget, Votes, Score, Runtime
  - *R² = 0.6958*, *RMSE ≈ $94.8M*

---

## 💡 Key Findings
- **Budget and Votes** are the strongest predictors of box office success.
- **Score and Runtime** show weak correlation with revenue.
- **Comedy, Action, and Drama** are the top 3 most popular genres.
- **Marvel Studios** leads in average gross revenue among production companies.
- **Prolific directors** (e.g., Woody Allen, Clint Eastwood) and actors (e.g., Nicolas Cage, Tom Hanks) heavily influence industry trends.
- The **COVID-19 pandemic** greatly disrupted the industry but also accelerated digital transformation (OTT platforms, 4D/5D theaters).

---

## 🎯 Strategic Recommendations
1. **Invest in High Budgets** for production, marketing, and talent.
2. **Engage Audiences** through social media and interactive content.
3. **Focus on Popular Genres** like comedy, action, and drama while experimenting with niche markets.
4. **Adapt to Global Disruptions** using OTT platforms and flexible release plans.
5. **Continue Data-Driven Decisions** by regularly analyzing trends and performance.

---

## 📁 Project Structure

```
MovieIndustryAnalysis/
├── CDS230_Final_Group2_Movies.ipynb         # All analyses and models
├── CDS230_Group2_FinalPresentationSlides.pdf
└── README.md  ← You are here
```

---

## 🛠️ Tools Used
- **Python** (pandas, seaborn, matplotlib, sklearn)
- **Jupyter Notebook**
- **PowerPoint** (Final Presentation)

---

## 📈 Sample Visuals
- Linear regression plots (Budget vs Gross)
- Genre popularity bar charts
- Distribution heatmaps
- Outlier visualizations for Budget and Gross

---

## 📌 Conclusion
This project provides a comprehensive overview of the dynamics within the movie industry. By combining statistical analysis, visualization, and predictive modeling, we gained actionable insights into what drives movie success. These findings can inform strategic decision-making in film production, marketing, and distribution.
