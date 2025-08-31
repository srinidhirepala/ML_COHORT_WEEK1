# 🛳️ Titanic Dataset EDA  

This repository contains an **Exploratory Data Analysis (EDA)** of the Titanic dataset using Python.  
The notebook/script performs data exploration, visualization, and derives key insights about passenger survival.  

---

## 📂 Dataset  
- The dataset used is the **Titanic dataset** (available via [Seaborn’s built-in datasets](https://seaborn.pydata.org/generated/seaborn.load_dataset.html) or [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic/data)).  
- If running locally or in Google Colab:  
  - By default, the script loads the Seaborn Titanic dataset.  
  - You can also upload `train.csv` from Kaggle and uncomment the CSV loading code.  

---

## 📊 EDA Workflow  

The notebook/script includes the following steps:  

1. **Library Setup** → Install and import required libraries.  
2. **Dataset Loading** → Load Titanic dataset (Seaborn or CSV).  
3. **Overview** → Shape, info, summary statistics.  
4. **Missing Values** → Identify and visualize missing data.  
5. **Univariate Analysis** → Explore distributions of survival, gender, age, etc.  
6. **Bivariate Analysis** → Relationships between survival and other features.  
7. **Correlation Analysis** → Encode categorical features & generate heatmap.  
8. **Survival Rates** → Survival probability by gender, class, and port.  
9. **Multivariate Visualization** → Combined plots of survival vs. multiple features.  
10. **Final Insights** → Summary of patterns in the dataset.  

---

## 📌 Key Insights  

- Majority of passengers did **not survive (~62%)**.  
- **Females had higher survival rates** than males.  
- **1st class passengers** had the highest survival probability, while 3rd class had the lowest.  
- **Children** had slightly better chances of survival.  
- Passengers from **Cherbourg (C)** port had higher survival rates than those from Southampton (S).  
- Strongest predictors of survival are **sex, class, and age**.  

---

## ⚙️ How to Run  

### 1. Clone the Repository  
```bash
git clone https://github.com/<your-username>/titanic-eda.git
cd titanic-eda```

### 2.Run in Jupyter/Colab
```bash
  pip install -r requirements.txt
  jupyter notebook```




