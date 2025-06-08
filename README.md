# 🌍 Leveraging Machine Learning to Identify Global Collaboration on SDGs

## 🔖 Introduction
The United Nations Sustainable Development Goals (SDGs) represent a universal call to action to end poverty, protect the planet, and ensure prosperity for all. Achieving these goals requires **strong global partnerships and collaboration**.

This project uses **machine learning techniques** to analyze and predict which countries are actively collaborating to promote the SDGs — with focus on:
- **SDG 17** (Partnerships for the Goals)
- **SDG 1** (No Poverty)
- **SDG 2** (Zero Hunger)

---

## ❓ Problem Statement

Progress on the SDGs is uneven, with some countries lagging in collaborative efforts. Identifying these countries is critical to improving international support and resource allocation.

### 🎯 Project Goals:
1. Analyze global collaboration on SDGs related to hunger and poverty  
2. Identify countries leading, lagging, or disconnected in these efforts  
3. Predict countries at risk of falling behind using historical data and socio-economic indicators  

---

## 📊 Dataset

We use the **Hunger, Poverty, and SDGs dataset** from Kaggle:  
[https://www.kaggle.com/code/gianlab/hunger-poverty-sustainable-developement-goals]

The dataset includes:
- Country-level data on hunger and poverty indicators  
- Measures of international collaboration related to SDGs  
- Socio-economic features such as GDP, education, and health indicators

---

## 🧠 Methodology

### 1. Data Preprocessing  
- Cleaning missing and inconsistent values  
- Normalizing numerical features  
- Encoding categorical data for modeling  

### 2. Feature Engineering  
- Created new variables to quantify collaboration intensity, hunger index, and poverty index  
- Combined multiple indicators into meaningful features  

### 3. Model Selection  
- Trained **Random Forest** and **Logistic Regression** models to classify countries by collaboration status  

### 4. Model Evaluation  
- Used **accuracy, precision, recall, and F1-score** to assess performance  
- Analyzed feature importance to understand key drivers of collaboration  

---

## 📈 Key Findings

- Countries with **higher GDP per capita** and **better education** tend to have higher collaboration levels  
- Developed countries in **Europe and North America** show more active partnerships  
- Our model achieved an **85% accuracy** in identifying non-collaborating countries, showing the promise of ML in SDG monitoring  

---

## 🌐 Impact & Relevance

- Supports **SDG 17** by providing a data-driven tool for tracking partnerships  
- Indirectly supports **SDG 1 & 2** by identifying areas where poverty and hunger remain high due to collaboration gaps  
- Helps international organizations prioritize aid and build effective partnerships  

---

## 🔮 Future Work

- Integrate real-time data on global aid and trade  
- Expand the model to cover **all 17 SDGs**  
- Develop an interactive dashboard for visualizing collaboration networks and predictions  

---

## ✅ Conclusion

Machine learning is a powerful tool for uncovering patterns in global collaboration. This project demonstrates how data analytics can help target international efforts, ensuring no country is left behind in achieving the SDGs.

---

## 👥 Authors

Group 61  
Lagos State University | PLP Academy  

---

## 🔗 GitHub Repository

[Add your GitHub repo link here]

---

## 📂 Repository Structure
