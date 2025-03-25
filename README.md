# **Bank Customer Churn Prediction**

## **By Sivan Itzhaki**

![download](https://github.com/user-attachments/assets/1dffe2dd-1586-4f6d-9677-cf84d366dfe6)


## **Customer Churn Prediction**   
The project focuses on **customer churn prediction** using **AutoML with H2O** to identify high-risk customers and enable proactive retention strategies.  
All models and their performance metrics were tracked using **MLflow** for reproducibility, monitoring, and comparison.  

---

## **Challenge**  
Customer churn is a critical issue for businesses, impacting revenue and long-term growth. Identifying customers at risk of leaving is challenging due to:  
- **Complex behavioral patterns** affecting churn decisions.  
- **Imbalanced data**, where churners are a minority.  

---

## **Solution: Machine Learning-Based Churn Prediction**  
Customer churn was predicted using a **Gradient Boosting Classifier (GBC) with AutoML**.  

---

## **Methodology**

### **Data Acquisition**  
The dataset was sourced from **Kaggle**, which provides real-world customer churn data, commonly used for predictive modeling in the banking sector.  

### **Data Cleaning & Feature Engineering**  
- **Column Removal & Creation**: Removed irrelevant columns and created new features to enhance model performance.  
- **Feature Transformation**: Applied **log transformation** and categorized numerical features for better interpretability.  
- **Encoding**: Performed **One-Hot Encoding** on categorical variables.  

---

### **Model Selection & Optimization**  
- **AutoML with H2O**: Evaluated two models – **Gradient Boosting Classifier (GBC)** and **Stacked Ensemble**.  
- **Performance Metric**: Optimized for **F1-score**, balancing precision and recall.  
- **Hyperparameter Tuning**: Fine-tuned using **Grid Search** to improve model performance.  
- **MLflow Tracking**: Logged model performance, parameters, and artifacts for experiment comparison and reproducibility.  

---

### **Evaluation & Interpretation**  
- **Feature Importance**: Identified **key churn predictors** (e.g., Age, Number of Products).  
- **SHAP Analysis**: Explained **how each feature impacts predictions**.  
- **Precision-Recall Curves**: Assessed model trade-offs.  

---

## **Outcome**  
A **churn prediction model**, supporting **data-driven retention strategies** by identifying at-risk customers and providing insights for proactive intervention.  

---

## **Future Improvements**  
- **Enhance feature engineering** (e.g., refine tenure representation, segment customers based on behavioral patterns).  
- **Explore alternative models** (e.g., SVM, KNN) for comparative performance evaluation.  
- **Align model objectives with business goals** (e.g., prioritize recall for maximum churn detection or precision to minimize unnecessary interventions).  
- **Segment-Based Churn Prediction**

---

