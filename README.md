# 🎬 Amazon Prime Video Analytics: EDA & AI-Driven Movie Success Prediction

## 📌 Project Overview
This project focuses on analyzing movie datasets by merging multiple sources and applying data analysis and machine learning techniques to predict movie success. The goal is to extract meaningful insights and build predictive models based on movie attributes.

## 📊 Exploratory Data Analysis (EDA)
We performed detailed EDA to understand the dataset and identify patterns:

- Distribution of IMDb Scores, Runtime, Votes, and Release Year  
- Box plots to detect outliers  
- Count plots for content type and age certification  
- Genre analysis to identify most common categories  
- Scatter/relationship analysis between features  
- Correlation heatmap to understand feature relationships  

📌 Total Visualizations: **15+ charts**

## 🤖 Machine Learning Models

### 🔹 Model 1: Classification (Movie Success Prediction)
- Algorithm: Logistic Regression / Random Forest  
- Target: Predict whether a movie is successful (1) or not (0)  
- Accuracy: **~85%**

### 🔹 Model 2: Regression (IMDb Score Prediction)
- Algorithm: Linear Regression  
- Target: Predict actual IMDb rating  
- Metrics Used:
  - Mean Squared Error (MSE)
  - R² Score

## 📊 Key Insights
- Most movies have ratings between **6 and 7**
- Movie runtime generally falls between **90–120 minutes**
- Popularity (votes) has a positive influence on ratings  
- Some outliers exist in both ratings and runtime  
- Dataset shows slight imbalance in successful vs non-successful movies  

## 🛠️ Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 🚀 Future Scope
- Use advanced models like Random Forest, XGBoost  
- Include more features like genre, cast, director  
- Improve prediction accuracy  
- Deploy the model using a web application  

## 📁 Project Structure
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Building (Classification & Regression)  
- Model Evaluation  

## 🎯 Conclusion
This project demonstrates how data analysis and machine learning can be used to understand movie performance and predict success. The results show that data-driven approaches can provide valuable insights for decision-making in the entertainment industry.

## 🙌 Acknowledgment
This project was developed as part of a learning exercise in data analysis and machine learning.
