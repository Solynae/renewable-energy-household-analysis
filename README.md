# Household Renewable Energy Usage and Cost Savings Analysis (2020–2024)

This project analyzes household renewable energy usage and its relationship with cost savings between 2020 and 2024.  
The study was conducted within **W-Code 2.0 – 3rd Term** under the theme **Accessible and Clean Energy**.

---

## 👥 Project Team
- Nazlıcan Ezeroğlu
- Nisa Kaşıkcı  
- Gizem Üner  
- Hilal Zerk Demirkan  

---

## 📊 Dataset Source

The dataset used in this project was obtained from **Kaggle**.

- Platform: Kaggle  
- Dataset name: **Global Renewable Energy Usage (2020–2024)**  
- Dataset slug: `global-renewable-energy-usage-2020-2024`  
- Time period: 2020–2024  
- Number of records: 1000  

---


## 🎯 Project Aim
The main goal of this project is to analyze the factors affecting renewable energy usage and household cost savings.  
Specifically, the study examines the impact of income level, household size, settlement type (urban/rural), regional differences, and government subsidies.

---

## 📊 Dataset Overview
- **File:** `Renewable_Energy_Usage_Sampled.csv`
- **Observations:** 1000
- **Features:** 12

The dataset includes information on energy source types, monthly usage, cost savings, income levels, household size, and geographic characteristics.

---

## 🧹 Data Preprocessing
Before analysis:
- The dataset was checked for missing values, and none were found.
- Categorical variables were converted into numerical form.
- Year-related columns were cast to appropriate numeric types.
- Per-capita energy usage and cost savings were calculated by dividing totals by household size.

---

## 📈 Exploratory Data Analysis (EDA)
During the exploratory analysis, various visualizations were used to examine:
- Distribution of renewable energy sources
- Energy usage trends from 2020 to 2024
- Regional preferences for energy sources
- Relationship between monthly energy consumption and cost savings
- Effects of income level and urban/rural residence on consumption and savings

---

## 🤖 Machine Learning Analysis
After the exploratory analysis, machine learning techniques were applied to better understand the determinants of cost savings.

In this stage:
- **Cost_Savings_USD** was selected as the target variable.
- Features such as energy source type, income level, household size, urban/rural status, and subsidy status were included.
- The data was split into training and test sets.
- A multiple linear regression model was built.
- Model performance was evaluated using error metrics and explanatory power.

The results indicate that cost savings are not driven by a single factor, but rather by the combined effect of multiple variables.

---

## 🔍 Key Findings
- The distribution of renewable energy sources is relatively balanced, with wind energy being one of the most commonly used sources.
- Energy usage trends vary over time, with noticeable shifts between energy sources.
- Income level and urban–rural differences do not independently determine consumption or savings.
- Low- and middle-income households can achieve savings comparable to high-income households.
- Wind energy shows a higher overall cost-saving potential compared to other sources.
- Cost savings depend on energy type as well as household characteristics, consumption levels, and regional factors.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## ▶️ How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/solynae/renewable-energy-household-analysis.git
cd renewable-energy-household-analysis
```

### 2. Install required dependencies

Make sure you have Python installed, then install the required libraries:

```bash
pip install -r requirements.txt
```

Alternatively, you can install the libraries manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open the Jupyter Notebook

Launch Jupyter Notebook with the following command:

```bash
jupyter notebook
```


Then open the file:

```bash
household_renewable_energy_analysis.ipynb
```

All analyses, visualizations, and machine learning steps can be found and executed inside this notebook.

Note: The dataset file (`Renewable_Energy_Usage_Sampled.csv`) must be located in the same directory as the notebook for the code to run properly.

```

## 📁 Project Structure
├── Renewable_Energy_Usage_Sampled.csv
├── household_renewable_energy_analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images/

```

---

## 📄 License
This project is licensed under the MIT License.

---

## 📌 Note
This project was prepared for educational purposes as part of the Gelecek Hayalim W-Code 2.0 program.

