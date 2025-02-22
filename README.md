# 🍔 McDonald's Customer Segmentation & Analysis

## 📖 Overview
This project analyzes customer preferences and behaviors using **McDonald's dataset**. The study involves **exploratory data analysis (EDA), clustering, and customer segmentation** using **K-Means and Hierarchical Clustering**. The goal is to identify meaningful customer segments based on their perceptions and behaviors.

---

## 🛠️ Problem Statement
McDonald's, a leading global fast-food chain, caters to a diverse customer base. The objective of this study is to:
- **Identify distinct customer segments** based on their preferences.
- **Analyze customer demographics and visit frequency**.
- **Understand the factors driving customer satisfaction and dissatisfaction**.

---

## ✨ Solution Approach
1. **Data Cleaning & Preprocessing**  
   - Removed duplicate values.  
   - Encoded categorical variables (Yes/No responses, Likert scale).  
   - Created an **Age Group** feature for better analysis.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized feature distributions using **Seaborn & Matplotlib**.  
   - Performed **Principal Component Analysis (PCA)** for dimensionality reduction.  
   - Generated **mosaic plots** to analyze customer preferences.

3. **Customer Segmentation**  
   - Applied **K-Means Clustering** to segment customers based on perceptions (e.g., "Yummy," "Cheap," "Healthy").  
   - Used **Hierarchical Clustering** to validate segment structures.  

4. **Segment Evaluation & Insights**  
   - Analyzed customer segments based on **gender, visit frequency, and age group**.  
   - Created **scatter plots** to compare customer preferences across segments.
  
---

## 📝 Key Findings
- **Segment 1 & 4**: Positive perception of McDonald's (liked by customers).  
- **Segment 2**: Customers strongly dislike McDonald's (perceive it as greasy, expensive, and disgusting).  
- **Segment 3**: Mixed opinions – some customers like it, some don't.  
- **Frequent visitors** tend to like McDonald's more than occasional visitors.

-  

## 📊 Libraries and Tools Used
- **Data Processing:** pandas, numpy  
- **Visualization:** seaborn, matplotlib  
- **Machine Learning & Clustering:** scikit-learn (K-Means, PCA, Agglomerative Clustering)  
- **Statistical Analysis:** statsmodels (Mosaic plots)  

## 🚀 How It Works
1. **Input:** Loads McDonald's customer dataset.  
2. **Processing:** Cleans data, encodes categorical features, applies PCA & clustering models.  
3. **Output:**  
   - Identified **4 customer segments**.  
   - Generated insights on **customer perception, demographics, and visit frequency**.

---

### 🔥 How to Run the Project
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels bioinfokit
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook "code.ipynb"
3. Explore the customer segments, visualizations, and clustering results.
