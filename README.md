# Titanic Survival Data Analysis
Exploratory Data Analysis on Titanic Dataset with Python code and explanations.

## 📌 Project Overview
This project analyzes the Titanic dataset to explore factors influencing passenger survival.  
The dataset is processed using Python and visualized through plots to uncover meaningful insights.

## 🎯 Objectives
- Explore the relationship between **Fare** and **Survival**.
- Investigate **gender-based survival rates**.
- Analyze the impact of **family size** on survival.

## 📂 Dataset
- **Source:** Titanic dataset (`titanic_dataset.csv`)
- **Columns of Interest:** Passenger details such as Fare, Gender, SibSp, Parch, and Survival status.

## 🛠️ Tools & Libraries
- **Python**
- **Pandas**
- **Matplotlib / Seaborn** (for data visualization)
- **Jupyter Notebook**

## 📊 Analysis Performed
1. **Fare vs Survival**  
   - Grouped passengers by survival status and compared average fare.  
   - Created box plots for visualization.

2. **Gender-based Survival**  
   - Crosstab between gender and survival.  
   - Computed survival percentages for males vs females.

3. **Family Size & Survival**  
   - Derived new column: `FamilySize = SibSp + Parch + 1`.  
   - Plotted survival rate against family size.

## 🚀 How to Run
1. Clone this repository:  
   ```bash
https://github.com/Satish-Saulagi-5/Titanic_EDA_Practice.git
