# **Bank Term Deposit Subscription Prediction**  

## **1. Project Overview**  
This project focuses on predicting customer subscription to term deposits using machine learning. The objective is to optimize marketing efforts, reduce costs, and improve conversion rates by identifying high-potential customers.  

### **Key Objectives:**  
- **Improve targeting efficiency** by identifying customers most likely to subscribe to term deposits.  
- **Reduce marketing costs** by minimizing outreach to non-potential customers.  
- **Enhance conversion rates** by optimizing telemarketing strategies.  
- **Provide business insights** to refine customer segmentation and improve future campaigns.  

## **2. Data Sources**  
- **Bank marketing dataset** (historical customer interactions and campaign outcomes).  
- **Economic indicators** such as interest rates, employment variation rates, and consumer confidence.  

## **3. Technologies Used**  
- **Programming Language:** Python (pandas, numpy)  
- **Visualization:** Matplotlib, Seaborn  
- **Statistics:** SciPy, Statsmodels  
- **Machine Learning:** Scikit-learn, Imbalanced-learn, LightGBM  
- **Model Evaluation:** F2-score, Precision, Recall, Confusion Matrix  
- **Version Control:** Git  
- **Development Environment:** Jupyter Notebook  

## **4. Project Structure**  

```
├── README.md          <- Project documentation.
├── data
│   ├── raw            <- Original dataset.
│   ├── processed      <- Cleaned and preprocessed dataset for modeling.
│
├── models             <- Saved trained models for prediction.
│
├── notebooks          <- Jupyter Notebooks with EDA, model training, and evaluation.
│
├── reports            <- Business insights, visualizations, and final analysis.
│   └── figures        <- Graphs and plots used in reporting.
│
├── requirements.txt   <- List of dependencies for project reproduction.
│
└── src                <- Source code for data processing and model training.
```  

## **5. Summary of Findings**  

### **5.1 Business Insights**  
- **Customer engagement is key**: Longer call durations and previous interactions increase the likelihood of subscription.  
- **Certain demographics respond better**: Retired individuals, students, and entrepreneurs have the highest subscription rates.  
- **Economic conditions matter**: Higher consumer confidence and stable employment rates correlate with higher conversions.  
- **Campaign timing impacts success**: Subscription rates peak in March, September, October, and December.  
- **Past campaign success predicts future interest**: Customers who previously subscribed are more likely to do so again.  
- **Mobile outreach is more effective**: Contacting customers via cellular results in better conversion rates than landlines.  

### **5.2 Actionable Recommendations**  

#### **Model Optimization:**  
- **Fine-tune classification thresholds** to reduce false positives without sacrificing recall.  
- **Improve feature engineering** by incorporating behavioral and time-based data.  
- **Explore alternative resampling techniques** such as SMOTE or hybrid sampling to balance class distribution.  
- **Implement automated model retraining** to adapt to changing customer behaviors.  

#### **Business Strategy Enhancement:**  
- **Prioritize high-potential customers** identified by the model to reduce wasted marketing efforts.  
- **Optimize telemarketing scripts** to increase engagement and call duration.  
- **Leverage economic trends** to align marketing efforts with favorable conditions.  
- **Personalize customer interactions** by segmenting marketing strategies based on occupation, financial status, and past engagement.  
- **Enhance retention strategies** with targeted follow-ups and loyalty programs for past subscribers.  

## **6. Contact**  
- **Name:** Bela Moneta & Rachmawati Hapsari Putri
- **Email:** belamoneta@gmail.com & putriemma2010@gmail.com
- **LinkedIn:** belamoneta & rachmawatihp