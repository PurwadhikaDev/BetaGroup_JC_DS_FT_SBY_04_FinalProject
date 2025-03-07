<h1> [Daegu Apartment Predict Price] </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve This project analyzes business data to extract insights, enhance decision-making, and identify key trends. The primary focus is to predict apartment sale prices, guiding property investments and optimizing real estate development strategies. Key business objectives include optimizing sales.

**Key Objectives:**  
- **Objective 1:** Analyze the relationship between key features (e.g., size, year built, number of facilities, and nearby amenities) and apartment sale prices to uncover pricing patterns.  
- **Objective 2:** Develop a regression-based machine learning model to accurately predict apartment sale prices.  
- **Objective 3:** Provide actionable insights for sellers to set competitive and market-aligned prices, reducing time on the market and maximizing profits.  
- **Objective 4:** Highlight valuable property features to attract potential buyers and optimize real estate development strategies.  

## 2. Data Sources
- [Dataset 1](link) - Description of dataset (e.g., Sales data for 2020–2023)


## 3. Technologies Used
- Programming Language: Python (pandas, numpy)
- Visualization: Matplotlib, Seaborn
- Statistic : scipy, statmodels
- Machine learning : scikit-learn, imblearn
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Findings  

### 5.1 Business Insight  
- Apartment prices are significantly influenced by features like size, age, nearby amenities, and location.  
- Incorporating additional features such as seasonal trends or proximity to key locations can improve prediction accuracy.  
- Outliers in the dataset can distort predictions, highlighting the need for robust preprocessing.  
- Regular updates with new data ensure the model remains relevant in a dynamic market.  

### 5.2 Actionable Recommendation  
- **Model Improvement:** Enhance predictions by adding new features (e.g., proximity to schools or transport) and improving outlier detection. Use advanced hyperparameter optimization techniques like Bayesian optimization.  
- **Real-time Integration:** Incorporate real-time data sources (e.g., market trends or neighborhood developments) to keep predictions dynamic.  
- **Business Adoption:**  
  - Integrate the model into pricing tools for sellers and real estate agents to set competitive prices.  
  - Provide a customer-facing tool for price insights to build trust and enhance user experience.  
  - Use predictions to guide targeted marketing and strategic pricing across property segments.  
- **Continuous Learning:** Implement automated model retraining with fresh data to adapt to market changes.  
- **Strategic Insights:** Utilize predictions for business intelligence, such as identifying high-value investment areas and creating data-driven negotiation strategies.

## 6. Contact
- Name: Rachmawati Hapsari Putri
- Email: putriemma@gmail.com
- Linkedin: www.linkedin.com/in/rachmawatihp
