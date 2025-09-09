# 📖 Project Report: IMDB Movie Success Prediction

## ✨ Introduction

Movies are more than just entertainment — they are big investments, and predicting their success is a challenge that excites both filmmakers and data scientists.
In this project, carried out during my time as a Data Analyst at Elevate Labs, I explored how audience reviews, ratings, and sentiment can be leveraged to predict a movie’s box office performance.

The goal was to combine machine learning with sentiment analysis and create meaningful insights through interactive dashboards.

---

## 📌 Methodology
   1. Data Collection & Preparation:
         Imported IMDB movie, rating, and review datasets.
         Cleaned and structured data for consistency and accuracy.

   2. Sentiment Analysis:
         Used VADER (Valence Aware Dictionary and sEntiment Reasoner) to measure positivity, negativity, neutrality, and compound sentiment in user reviews.
         Generated average sentiment scores at the movie and genre level.

   3. Predictive Modeling with Random Forest:
         Developed a Random Forest Regressor to predict box office collections using features such as IMDB ratings, sentiment scores, and genre data.
         Tuned hyperparameters for better accuracy and model stability.
         Evaluated the model using R², MAE, and RMSE to assess predictive performance.
   4. Genre-Wise Insights
         Segmented movies by genre to analyze audience response.
         Identified that Drama and Action genres showed stronger correlations between sentiment and success.

   5. Visualization & Storytelling
      Designed Power BI dashboards to make insights interactive and easy to explore.
      Dashboards highlighted sentiment patterns, predicted vs actual box office performance, and genre-wise comparisons.
---

## 🛠️ Tools & Technologies
- **Programming and libraties:** Python(pandas, numpy, sklearn, vaderSentiment, matplotlib, seaborn)  
- **Visualization:** Power BI(dashboard creation & storytelling)  
- **Environment:** Jupyter Notebook, Power BI Desktop
- **Machine Learning:** Random Forest Regressor

---

## 📊 Key Findings
- Audience sentiment significantly influenced movie success.
- Genres such as Drama and Action were more sentiment-driven than others.
- The Random Forest Regressor provided strong predictive accuracy, outperforming simpler regression techniques.
- Power BI dashboards transformed raw data into decision-ready insights.

---

## 🌟 Conclusion
This project demonstrated how **data science and storytelling** with data can provide valuable insights into the entertainment industry.
By analyzing IMDB data, applying sentiment analysis, and using a **Random Forest model**, I was able to uncover patterns that explain why certain movies succeed while others underperform.

Most importantly, the **Power BI dashboards** made the findings accessible to stakeholders, enabling better data-driven decisions.

---
