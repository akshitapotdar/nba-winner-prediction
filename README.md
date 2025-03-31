
# 🏀 Predicting NBA Game Winners Using Machine Learning

This project demonstrates the practical application of machine learning to sports analytics, specifically predicting NBA basketball game outcomes. Combines real-world data, advanced ML techniques, and strong performance results to showcase end-to-end data science capability.

---

##  Overview

- **Domain:** Sports Analytics (NBA)
- **Objective:** Predict the winner of NBA games using historical performance data
- **Best Model:** Random Forest (achieved **90% accuracy**)
- **Techniques:** Feature Engineering, Time-Series Cross-Validation, Model Optimization, Advanced Evaluation Metrics

---

##  Dataset

- **Source:** [Basketball Reference](https://www.basketball-reference.com/)
- **Size:** 17,772 games | 151 features
- **Key Features:**
  - Team stats: PTS, FG%, 3P%, REB, AST, STL, BLK, TO
  - Game context: Home/Away, Opponent ID, Date
  - Advanced metrics: PER, TS%, rolling averages, win ratios

---

##  Methodology

### 1. Data Preprocessing
- Cleaned raw HTML stats with BeautifulSoup
- Normalized and standardized features using `MinMaxScaler`
- Engineered rolling features and match-specific metrics

### 2. Exploratory Data Analysis (EDA)
- Identified trends in scoring, outliers, and top team performance
- Visualized win distribution and offensive dominance across teams

### 3. Model Development
- Algorithms used:
  - Ridge Classifier
  - Logistic Regression
  - Linear SVC
  - **Random Forest** (top performer)
- Applied Sequential Feature Selection to extract 30 key predictors
- Used `TimeSeriesSplit` for validation to avoid data leakage

### 4. Optimization
- Hyperparameter tuning via `GridSearchCV`
- Evaluation using **accuracy**, **precision**, **recall**, and **F1-score**

---

## 📈 Results

| Model                  | Accuracy |
|------------------------|----------|
| Ridge Classifier       | 78.5%    |
| Linear SVC             | 63.2%    |
| Logistic Regression    | 79.0%    |
| Random Forest          |**90.0%** |

- **Random Forest** excelled at capturing complex patterns and interactions.
- Feature selection significantly boosted model interpretability and performance.

---

## 🔹 Highlights for Recruiters
- Delivered **90% prediction accuracy** on real-world NBA data
- End-to-end pipeline: scraping → preprocessing → modeling → evaluation
- Strong collaboration, documentation, and performance tuning
- Readable, reproducible, and extensible for future work (e.g., real-time betting, fantasy sports)

---

## 🤝 Let's Connect

**Akshita Potdar**  
Email: akshitapotdar@gmail.com  
LinkedIn: [linkedin.com/in/akshitapotdar](https://www.linkedin.com/in/akshitapotdar)

---

> "This project proves that with the right data, features, and models — even the outcome of an NBA game can be predicted."
