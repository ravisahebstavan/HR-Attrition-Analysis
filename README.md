# HR Employee Attrition Analysis & Dashboard

### Author
Stavan Ravisaheb

---

### Project Overview
This project analyzes employee attrition in a company using a comprehensive HR dataset. The goal was to identify key factors influencing attrition and create an interactive dashboard to provide actionable insights for HR management and decision-making.

### Technologies Used
* **Python:** Pandas, NumPy, and Scikit-learn for data cleaning, preprocessing, and machine learning modeling.
* **Seaborn & Matplotlib:** Data visualization for exploratory analysis and correlation heatmaps.
* **Jupyter Notebook:** Workflow documentation and model building.
* **Tableau:** To create an interactive visualization of attrition insights.

### Project Steps
1. **Data Preparation (Python):**  
   The HR dataset was cleaned to remove missing or inconsistent entries, encode categorical variables, and prepare numeric columns for analysis. A new CSV file (`HR-Employee-Attrition-Cleaned.csv`) was created for modeling and dashboard purposes.

2. **Exploratory Data Analysis (EDA):**  
   Conducted correlation analysis to identify factors most associated with employee attrition. Visualizations included correlation heatmaps for a complete understanding of the data.

3. **Machine Learning Model (Python):**  
   - Target column `Attrition` converted to numeric.  
   - Categorical features encoded and data standardized.  
   - Logistic Regression model built and evaluated for accuracy.  
   - Feature importance identified key attrition drivers.

4. **Interactive Dashboard (Tableau):**  
   The dashboard provides actionable HR insights through the following visuals:  
   - **5 Key KPIs** summarizing overall workforce attrition and key metrics.  
   - **Attrition by Department and Income Group** to identify high-risk employee segments.  
   - **Attrition by Age Group** to highlight vulnerable age brackets.  
   - **Job Satisfaction vs Performance Rating** to understand employee engagement and outcomes.  
   - **Average Monthly Income vs Years At Company** to analyze compensation patterns in relation to attrition.  
   This setup helps HR identify trends, spot risk areas, and plan retention strategies effectively.

### Cleaned Data
The cleaned dataset (`HR-Employee-Attrition-Cleaned.csv`) is included to allow reproducing the analysis and modeling. It contains all processed numeric and categorical features used for correlation analysis and machine learning.

### Final Dashboard
The completed HR Attrition dashboard is included to present actionable insights for HR decision-making. It provides a clear visual understanding of key attrition drivers and employee patterns.
