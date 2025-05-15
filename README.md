# 🐶 Dog Longevity Predictor - Machine Learning Research

*A machine learning project to predict dog lifespan based on breed attributes, developed by Horizon Campus IT students*

## 📌 Abstract

This research analyzes attributes like breed score, size, child-friendliness ("score for kids"), and lifetime cost to predict canine longevity. We implemented and compared multiple machine learning models (Linear Regression, Random Forest, SVR, XGBoost) with SVR emerging as the best performer (R²=0.90, MSE=0.39). Findings reveal significant correlations between non-genetic factors and lifespan.

## 👥 Research Team

  Name  ID 

| Mr. Fernando | ITBNM-2110-0016
| Mr. Hennayaka | ITBNM-2110-0021 
| Mr. Silva | ITBNM-2110-0052 
| Mr. Wanigasekara | ITBNM-2110-0088 
| Mrs. Begam | ITBNM-2110-0006 

## 🛠️ Technical Implementation

### Tech Stack

- **Python 3.8+**
- **Machine Learning**:
  
  - Scikit-learn
    
  - XGBoost
    
  - Support Vector Regression
    
- **Data Analysis**:
  
  - Pandas
    
  - NumPy
    
  - Matplotlib/Seaborn
    
- **Environment**:
  
  - Jupyter Notebook

## 🔑 Key Findings

1. **Top Predictive Features**:
   
   - Breed size (R² impact: 0.42)
     
   - Lifetime cost (R² impact: 0.38)
     
   - Child-friendliness score (R² impact: 0.15)

3. **Model Performance**:
   
   | Model | MSE | R² Score |
   
   
   | SVR | 0.39 | 0.90 |
   
   | Random Forest | 0.83 | 0.79 |
   
   | XGBoost | 1.14 | 0.72 |

5. **Practical Implications**:
   
   - Smaller breeds typically live longer
     
   - Higher care costs correlate with increased longevity
     
   - Child-friendly breeds show moderate lifespan advantages
  
   - 
📊 jupyter lab

-Execute notebooks in order:

-Data cleaning & preprocessing

-Exploratory data analysis

-Model training & evaluation

-Sample Visualization

-Feature Importance

📚 Research Components

Methodology

-Data Collection: 87 breeds from Kaggle

-Preprocessing:

-Min-Max scaling

-Polynomial feature engineering

-Models Evaluated:

-Linear Regression

-Decision Trees

-Random Forest

-SVR (Best performer)

-XGBoost

Key Contributions

-Novel focus on non-genetic factors

-Comparative analysis of ML approaches

-Practical framework for breeders/veterinarians

📜 License
Academic Use Only - Contains proprietary research data

📬 Contact
Faculty Advisor: Daminda Herath
Faculty of IT
Horizon Campus, Sri Lanka
horizon.edu.lk
