# 📱Digital Wellness Analysis🧠
---

## 📌 Project Overview  
- This analysis investigates the relationship between digital consumption habits and psychological stress using a dataset of 100,000 records.   
- The workflow encompasses data cleaning, exploratory data analysis (EDA), feature engineering, and the development of a predictive model to identify key drivers of mental wellness.

---
## 📂Dataset
The dataset contains user digital lifestyle features such as:

- Screen time hours
- Hours spent on TikTok
- Number of social media platforms used
- Sleep hours
- Mood score
- Stress level (target variable)

----
 ## 🛠️ Technical Stack
- Language: Python

- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

- Methodology: Linear Regression, Correlation Analysis, Data Normalization

---

## 🔄 Project Workflow

### 1. Data Loading
The dataset is loaded using **Pandas**.  

### 2. Data Integrity Checks
- Checked dataset shape
- Verified missing values
- Identified duplicate rows

### 3. Data Cleaning
- Removed duplicate rows to ensure clean data.

### 4. Feature Engineering
New features were created to better represent digital behavior:

- **TikTok Usage %**
- **Social Media Usage %**

These represent the percentage of total screen time spent on specific activities.


### 5. Exploratory Data Analysis (EDA)

#### Statistical Summary
Basic statistics were analyzed to understand the data distribution.

#### Correlation Analysis
A correlation matrix was generated to identify relationships between features and stress level.  

**Key observations:**
- **Sleep hours** show a strong negative correlation with stress.
- **Screen time hours** show a moderate positive correlation with stress.
- **Hours on TikTok** also increase stress levels.


### 6. Machine Learning Model

A **Linear Regression model** was used to predict stress levels.

Steps:
- Split data into **training and testing sets**
- Train the model
- Evaluate performance

### Model Performance

- **R² Score:** ~0.75  
- **Mean Squared Error:** ~1.06

This indicates that the model explains around **75% of the variance in stress levels**.

### 7. Feature Importance

Feature coefficients were analyzed to understand which habits influence stress the most.

Key insights:
- **Sleep hours** significantly reduce stress
- **Screen time** increases stress
- **TikTok usage** also contributes to higher stress levels

### 8. Model Evaluation

A **Predicted vs Actual Stress Plot** was created to visualize model accuracy.

----

## 📊Key Insights

- Increasing **sleep hours** is strongly associated with lower stress.
- Higher **screen time** tends to increase stress levels.
- Time spent on **short-form content platforms** like TikTok correlates with higher stress.
- Mood score also plays an important role in mental well-being.

---
## 💡Strategic Recommendations
Based on the data-driven insights, two primary recommendations were formulated for digital wellness interventions:  

### 😴 **Prioritize 'Sleep Gain' over 'Screen Loss':**  
- The data suggests that increasing sleep by one hour is statistically more effective at reducing stress than decreasing screen time by the same duration.   
- Wellness strategies should prioritize sleep hygiene as the most powerful defense against digital-induced stress.

### ⏳ **Limit Total Duration, Not Just App Diversity:**  
- Total daily hours spent on high-intensity platforms is the primary driver of stress, regardless of the variety of apps used.   
- Effective management should focus on hard limits for total daily screen hours rather than managing the number of different platforms visited.


----
## 🔮Future Improvements

- Try **more ML models** 
- Build an **interactive dashboard (Power BI)**



-----
## 👩🏻‍💻**Author**

**Muskan Anand**  
📧 Email: anandmuskan0706@gmail.com















