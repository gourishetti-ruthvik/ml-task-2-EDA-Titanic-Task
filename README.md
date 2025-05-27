# Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective

This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** using Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly. The goal is to uncover key patterns and relationships in the data using descriptive statistics and visualizations.

---

## Folder Structure
├── titanic.csv # Dataset file  
├── EDA_Titanic.ipynb # Jupyter Notebook with full analysis  
└── README.md  


---

## Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Plotly (for interactive visuals)
- NumPy

---

## Dataset Description

The Titanic dataset contains data about the passengers aboard the Titanic. Key columns include:

- `Survived` — 0 = No, 1 = Yes  
- `Pclass` — Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `Name`, `Sex`, `Age` — Demographic features  
- `SibSp`, `Parch` — Family relationships aboard  
- `Ticket`, `Fare` — Ticket info  
- `Cabin`, `Embarked` — Additional travel details  

---

### Summary Statistics
- Generated basic stats like **mean**, **median**, **mode**, and **standard deviation** for numerical features.
- Identified missing values and basic data issues.

### Visualizations
- **Histograms** for Age, Fare, etc.
- **Boxplots** to detect outliers.
- **Correlation Heatmap** for numeric features.
- **Pairplots** to observe relationships.
- **Plotly scatter plot** for interactive insights.

### Key Insights
- Majority of survivors were **women and children**.
- **1st class passengers** had the highest survival rate.
- **Younger passengers** had better chances of survival.
- Fare has a **long-tailed distribution** (many low fares, few very high).

---

## Sample Visuals
![image](https://github.com/user-attachments/assets/3934d0ae-e3fe-4479-8700-6285e3c84df6)

![image](https://github.com/user-attachments/assets/b883f0d9-1d40-44fa-9a0d-7488e3e2de51)


## Learning Outcomes

- How to perform structured EDA using Python
- Use of various visualization techniques for better storytelling
- Drawing real-world insights from raw datasets
- How to clean and prepare data for further analysis or ML

