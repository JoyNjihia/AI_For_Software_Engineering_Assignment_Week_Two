
# 🌍 Leveraging Machine Learning to Identify Global Collaboration on SDGs

## 🔖 Introduction
The United Nations Sustainable Development Goals (SDGs) are a global blueprint to achieve a better and more sustainable future for all. Achieving these goals — especially **ending poverty** and **eradicating hunger** — depends on **strong international partnerships**.

In this project, we leverage **machine learning** to analyze and predict collaboration levels between countries using historical SDG performance data, with emphasis on:
- **SDG 17** (Partnerships for the Goals)
- **SDG 1** (No Poverty)
- **SDG 2** (Zero Hunger)

---

## ❓ Problem Statement

Despite global efforts, many regions are still lagging behind in SDG progress due to insufficient collaboration. Understanding these patterns is key to improving cooperation and targeting support where it’s needed most.

### 🎯 Project Objectives:
1. Analyze global collaboration on sustainable development  
2. Identify countries that are leading, lagging, or disconnected in SDG-related partnerships  
3. Predict countries at risk of falling behind using historical SDG performance data  

---

## 📊 Dataset

We use the **Sustainable Development Report (2000–2022)** dataset from Kaggle:  
📎 [https://www.kaggle.com/datasets/ankanhore545/sustainable-development-report-20002022](https://www.kaggle.com/datasets/ankanhore545/sustainable-development-report-20002022)

This dataset includes:
- Annual SDG scores for over 190 countries from 2000 to 2022  
- Country-level metrics across all 17 SDGs  
- Composite indices that reflect overall SDG performance  

---

## 🧠 Methodology

### 1. Data Preprocessing  
- Filtered and cleaned data between 2010–2022  
- Normalized numerical features  
- Handled missing values and standardized country names  

### 2. Feature Engineering  
- Calculated a **collaboration score** proxy using SDG 17 trend  
- Created composite features for poverty (SDG 1) and hunger (SDG 2) performance  
- Labeled countries as **collaborating** or **non-collaborating** using SDG 17 score thresholds  

### 3. Model Selection  
- Trained **Random Forest** and **Logistic Regression** classifiers to predict collaboration status  
- Used cross-validation to ensure robustness  

### 4. Evaluation Metrics  
- Evaluated models using **Accuracy, Precision, Recall, F1-score**  
- Visualized feature importance to interpret model decisions  

---

## 📈 Key Findings

- Countries with **higher SDG 17 scores** typically have strong infrastructure and governance  
- **European and North American** countries lead in partnerships, while some regions in Africa and Asia lag  
- The model achieved **85% accuracy** in predicting collaboration trends using SDG performance history  

---

## 🌐 Impact & Relevance

- Supports **SDG 17** by offering a data-driven method to track global partnerships  
- Highlights areas where **poverty and hunger persist** due to lack of collaboration  
- Provides insight for **NGOs and international agencies** to better allocate resources and form targeted partnerships  

---

## 🔮 Future Work

- Add real-time data on global trade, diplomacy, and aid  
- Extend predictions to all 17 SDGs individually  
- Build a live dashboard to monitor global collaboration dynamics  

---

## ✅ Conclusion

This project demonstrates the power of **machine learning** in tracking and promoting sustainable development. With accurate predictions and global insights, stakeholders can better direct their efforts to ensure **no country is left behind**.

---

## 👥 Authors

**Group 61**  
 
1. Joyce Njihia - nyamburanjihia@gmail.com
2.  Gospel Arinze - gospelarinzestuff@gmail.com
3.Ling Mukiri - lingmukiri13@gmail.com
4. Juma Calvin - jumacavin28@gmail.com
5.EstherTrizar  - esthertrizar@gmail.com

---

## 🔗 GitHub Repository

[ ]

---

## 📂 Repository Structure 
