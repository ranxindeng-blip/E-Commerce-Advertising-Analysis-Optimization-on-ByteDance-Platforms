# E-Commerce Advertising Analysis & Optimization on ByteDance Platforms

## Project Overview
This project analyzes three months of advertising data from an e-commerce brand running multiple ad formats (in-feed ads, splash ads, and brand ads) on ByteDance platforms (Douyin, Toutiao, Xigua Video). The goal was to evaluate campaign performance and uncover optimization opportunities through advanced analytics, visualization, and causal inference techniques.

---


## 🔧 Workflow
1. **Environment Setup & Data Import**
  - Configured environment and imported raw campaign data.

2. **Data Cleaning & Preprocessing**
  - Optimized data types and standardized formats.
  - Detected outliers using IQR and Z-score, handled via capping.
  - Engineered features and created derived metrics for analysis.

3. **Exploratory Visualization**
  - Campaign-level overview with advanced and interactive visualizations.
  - Built dynamic dashboards to explore key metrics.

4. **User Segmentation & Platform Performance**
  - Identified high-value user segments and platform-level performance insights.
  - Validated findings with statistical significance testing.
  - Applied clustering models to segment users more precisely.

5. **Time Series & Predictive Modeling**
  - Conducted trend decomposition to identify long-term vs. seasonal patterns.
  - Built predictive models (Logistic Regression, Random Forest) to forecast conversions.

6. **Advanced Analytical Techniques**
  - Attribution Modeling: Compared first-click, last-click, linear, and time-decay attribution to evaluate drivers of conversion value.
  - Causal Inference: Using Regression Discontinuity (RD) and Difference-in-Differences (DID), analyzed the impact of a budget increase on revenue, conversions, and ROAS.

7. **Business Insights & Optimization Recommendations**
  - Core findings on platform performance, best-performing user segments, time patterns, budget allocation, and ad type effectiveness.
  - Data-driven short-term optimization strategies, including budget reallocation, time optimization, and creative/ad-type adjustments.


## 📈 Key Takeaways
  - Identified ROI-efficient user cohorts and time windows.
  - Highlighted budget inefficiencies through causal inference analysis.
  - Provided actionable recommendations adopted in pilot campaigns, leading to improved allocation and targeting strategies.

## 🛠️ Tools & Techniques
  - Programming & Analytics: Python (pandas, NumPy, scikit-learn)
  - Visualization: Plotly, Power BI, Matplotlib, Seaborn
  - Statistical Methods: ANOVA, Clustering, Attribution Models, RD, DID
  - Machine Learning: Logistic Regression, Random Forest
