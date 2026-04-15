# 🧠 Mental Health Treatment Prediction Using Machine Learning

## 📌 Project Overview
This project applies machine learning techniques to predict whether an individual is likely to seek mental health treatment based on workplace, personal, and demographic factors. The goal is to identify key indicators influencing mental health decisions and build a predictive classification model using structured survey data.

# 📂 Dataset Description

**Source:** Open-source survey on mental health in tech workplaces  
**Total Records:** 1259 entries (after preprocessing)

## 📊 Features Include:
- Age  
- Gender  
- Country  
- self_employed  
- family_history  
- treatment *(Target variable)*  
- work_interfere  
- no_employees  
- remote_work  
- tech_company  
- benefits  
- care_options  
- wellness_program  
- seek_help  
- anonymity  
- leave  
- mental_health_consequence  
- phys_health_consequence  
- coworkers  
- supervisor  
- mental_health_interview  
- phys_health_interview  
- mental_vs_physical  
- obs_consequence  


# 🛠️ Tools & Libraries Used

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  


# 🧹 Data Preprocessing

- Removed invalid age values (e.g., <18 or >100)  
- Standardized categorical variables (e.g., gender normalization)  
- Handled missing values using mode/median imputation  
- Converted categorical features into numerical format using Label Encoding  
- Ensured dataset consistency for machine learning modeling  


# 📊 Exploratory Data Analysis (EDA)

## 🔍 Key Insights:
- Majority of respondents were aged between 20–35 years  
- Individuals with a family history of mental illness are more likely to seek treatment  
- Workplace benefits and supportive environments positively influence mental health treatment decisions  
- Remote work and workplace flexibility also impact mental health outcomes  

## 📈 Correlation Analysis:
- Strong correlation observed between:
  - family_history  
  - care_options  
  - treatment (target variable)  


# 🤖 Model Building

- Algorithm used: Random Forest Classifier  
- Train/Test Split: 80% training, 20% testing  
- Input Features (X): All columns except `treatment`  
- Target Variable (y): `treatment`  


# 📈 Model Evaluation

## 🎯 Performance Metrics:
- Accuracy: ~84%  
- Precision: ~0.85  
- Recall: ~0.84  
- F1-score: ~0.84  

The model demonstrates strong performance in classifying individuals likely to seek mental health treatment.


# 🧠 Key Findings

- Family history is one of the strongest predictors of mental health treatment-seeking behavior  
- Workplace support systems (benefits, care options) significantly influence decisions  
- Remote work environment also contributes to mental well-being patterns  
- Socio-workplace factors play a major role in mental health outcomes  


# 🚀 Conclusion

- The Random Forest model achieved approximately 84% accuracy in predicting mental health treatment behavior  
- Workplace and personal history-related features were the most influential predictors  
- The model provides meaningful insights into mental health patterns in workplace environments  


# 🔮 Future Enhancements

- Apply hyperparameter tuning to improve model performance  
- Compare with advanced models like SVM, XGBoost, or Gradient Boosting  
- Build a web-based application using Flask or Streamlit  
- Integrate NLP techniques for analyzing open-ended survey responses  
- Deploy model for real-time organizational mental health analysis  


# 👨‍💻 Author

Pogalla Bhargavi
B.Tech Computer Science Student  
