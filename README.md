# Amazon Customer Behavior & Recommendation Analysis

## Project Overview
This project analyzes customer behavior on Amazon using survey-based data to understand purchasing patterns, shopping satisfaction, review reliability, and the effectiveness of the recommendation system. The analysis focuses on extracting actionable insights through data cleaning, exploratory data analysis, customer segmentation, clustering, and visualization techniques.

This project was completed as part of the **Internshala Data Science Training Program**, following the official problem statement and academic guidelines provided during the training.

---

## Introduction
Customer behavior analysis plays a crucial role in improving user experience on e-commerce platforms. This project aims to study how customers interact with Amazon in terms of purchase frequency, browsing behavior, satisfaction levels, reviews, and recommendation usefulness, and to derive meaningful insights that can support better personalization strategies.

---

## Project Objectives
- Understand customer purchasing and browsing behavior
- Analyze shopping satisfaction and review reliability
- Segment customers based on behavioral patterns
- Apply clustering techniques for behavioral grouping
- Evaluate the impact of recommendations on customer satisfaction
- Provide actionable insights to improve recommendation systems

---

## Dataset Description
The dataset consists of customer survey responses related to:
- Purchase frequency
- Product search methods
- Shopping satisfaction
- Review importance and reliability
- Recommendation usefulness
- Behavioral and demographic attributes

---

## Project Workflow & Tasks

### Task 1: Data Cleaning & Preparation
- Removed duplicate columns and inconsistencies
- Handled missing values appropriately
- Converted rating-related columns to numeric format
- Standardized categorical variables

**Key Insight:**  
The dataset was cleaned and prepared to ensure reliable and accurate analysis.

---

### Task 2: Descriptive Behaviour Analysis
- Analyzed purchase frequency distribution
- Studied product search methods
- Visualized shopping satisfaction levels

**Key Insight:**  
Customers show varied purchasing behavior, with keyword search being the most preferred product discovery method. Satisfaction levels are mixed, indicating scope for improvement.

---

### Task 3: Customer Segmentation & Clustering
- Segmented customers into:
  - Frequent Buyers
  - Occasional Shoppers
  - At-Risk Customers
- Applied K-Means clustering on behavioral variables
- Compared clustering results with rule-based segmentation

**Key Insight:**  
Distinct customer groups were identified, and clustering results aligned well with predefined behavioral segments.

---

### Task 4: Recommendation & Review Analysis
- Analyzed the relationship between recommendation usefulness and shopping satisfaction
- Studied the impact of review reliability on rating accuracy
- Performed correlation analysis

**Key Insight:**  
Recommendation usefulness shows a near-zero correlation with satisfaction, while review reliability positively influences perceived rating accuracy.

---

### Task 5: Visualization & Summary of Insights
- Created interactive and static visualizations using Plotly, Seaborn, and Matplotlib
- Summarized key behavioral and recommendation insights

**Key Insight:**  
1. Purchase Frequency Distribution
- Customers are almost evenly distributed across all purchase frequency categories.
- No single purchase frequency (weekly, monthly, less frequent) clearly dominates.
- This indicates diverse shopping behavior rather than a strongly loyal or highly frequent customer base.
2. Product Search Method Distribution
- Keyword search is the most commonly used product search method.
- Category browsing, filters, and other methods are used less frequently but still by a significant number of customers.
- This shows customers prefer direct searching over exploratory browsing.
3. Shopping Satisfaction Distribution
- Shopping satisfaction scores are fairly evenly spread from 1 to 5.
- There is no strong skew toward very high satisfaction.
- This indicates moderate and mixed customer satisfaction, consistently high satisfaction.
4. Recommendation Usefulness vs Shopping Satisfaction
- The correlation value between Recommendation Usefulness and Shopping Satisfaction is –0.00011, which is almost zero.
- This indicates no meaningful relationship between how useful customers find recommendations and their overall shopping satisfaction.
- This suggests that customer satisfaction is likely influenced by other factors such as pricing, delivery experience, product quality, or overall platform usability rather than recommendations alone.


---

## Tools & Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Plotly
- Scikit-learn (StandardScaler, K-Means)
- Google Colab / Jupyter Notebook

---

## 🏁 Conclusion
This project demonstrates an end-to-end data science workflow, from data preprocessing to advanced analysis and visualization. The findings highlight the importance of customer segmentation, behavioral insights, and trusted reviews in improving recommendation systems and overall customer experience.

---
