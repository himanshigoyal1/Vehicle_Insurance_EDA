# Vehicle Insurance Analysis 🚗 | Exploratory Data Analysis Project

This project involves an in-depth Exploratory Data Analysis (EDA) of a vehicle insurance dataset to uncover patterns influencing customer insurance purchase decisions. The goal is to derive actionable insights to support business strategies in customer targeting, premium pricing, and risk profiling.

---

## 📌 Objective

To analyze behavioral and demographic attributes of potential insurance buyers and identify the key drivers of purchase interest (`Response`). This dataset and analysis serve as a foundation for building predictive models for insurance conversions.

---

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Dataset**: 381,109 records × 12 features
- **Environment**: Google Colab

---

## 📊 Business Context

The vehicle insurance industry faces challenges in converting leads into customers. This analysis assists in:

- Identifying high-potential customer segments
- Improving targeting efficiency in marketing campaigns
- Optimizing premium pricing strategies
- Laying the foundation for predictive modeling

---

## 📁 Dataset Overview

- **Customer Demographics**: Age, Gender, Region
- **Vehicle Information**: Age of vehicle, Damage history
- **Policy History**: Previously insured, Driving license, Premium amount
- **Sales Metrics**: Sales channel, Relationship vintage
- **Target Variable**: `Response` (0 = Not Interested, 1 = Interested)

---

## 🔍 Key Insights

| Category | Insights |
|---------|----------|
| **Customer Behavior** | Most interested customers are between ages 30–50, often not previously insured. |
| **Vehicle Insights** | Customers with newer or previously damaged vehicles are more likely to buy insurance. |
| **Premium Trends** | Optimal pricing band lies below ₹60,000; higher premiums reduce conversion. |
| **Geographic Patterns** | Regions like 28, 41, and 11 show high response rates — strong targets for campaigns. |
| **Sales Channels** | A few sales channels dominate customer acquisition; optimizing them can improve ROI. |
| **Customer Loyalty** | Longer customer engagement (Vintage) slightly increases purchase interest. |

---

## 📈 Visualizations & Techniques

- **Univariate**: Countplots, Boxplots, Histograms
- **Bivariate**: Gender vs Response, Vehicle Age vs Response
- **Multivariate**: Pairplot, Correlation Heatmap
- **Outlier Handling**: IQR-based filtering of `Annual_Premium`

Visual insights were generated after each plot, emphasizing real business value.

---

## 🧹 Data Preparation

- Dropped redundant `id` column
- Handled outliers in `Annual_Premium`
- Verified absence of missing values
- Used subset sampling for heavy plots (pairplots/scatter)

---

## 💼 Business Value

This project demonstrates:

- Ability to translate raw data into business-relevant insights
- Data-driven decision-making in product and marketing strategies
- Prepared data ready for supervised learning classification models

---




## 📌 Potential Extensions

- Train a Logistic Regression or Random Forest model to predict `Response`
- Build a Streamlit dashboard to interactively explore patterns
- Apply customer segmentation using K-Means clustering

---
## 📬 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/himanshi-goyal1)
- 📧 himanshigoyal1250@gmail.com

---

> ⭐ *If you found this project insightful, please star the repo and feel free to share or fork it!*
