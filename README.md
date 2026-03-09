# 📞 Telecom X: Customer Churn Analysis

## 📝 Project Overview
This project identifies the key factors driving customer attrition (**Churn**) at **Telecom X**. Using a dataset of 7,043 customers, I performed data cleaning, feature engineering, and exploratory data analysis (EDA) to provide actionable insights for retention strategies.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

---

## 🔍 Key Insights from the Analysis

### 1. The Churn Profile: Contracts & Payments
The analysis clearly identifies that **Month-to-month** contracts are the primary churn driver. Additionally, customers using **Electronic Checks** show a much higher tendency to leave compared to automated payment methods.

> <img width="1311" height="525" alt="churn_by_contrat" src="https://github.com/user-attachments/assets/b3cbfdee-6e9c-4630-8969-83e76121c6a8" />

### 2. High-Value Attrition: Fiber Optic
A critical finding was that **Fiber Optic** users have a higher churn rate despite it being a premium service. This suggests that price sensitivity (higher `MonthlyCharges`) or service stability may be impacting these high-value customers.

> <img width="1311" height="525" alt="churn_by_internet" src="https://github.com/user-attachments/assets/07c7640f-5895-49d3-85c7-f3081ad28eb2" />



### 3. Tenure & The "Early Exit" Phenomenon
There is a massive spike in churn during the first **1–6 months** of service. However, customers who stay past the 24-month mark show significantly higher loyalty, indicating that the initial onboarding experience is vital.

> <img width="1322" height="525" alt="churn_tenure" src="https://github.com/user-attachments/assets/457200d9-940a-4e0c-af3e-b95df113a91c" />


### 4. Feature Correlations
The heatmap confirms that `Tenure` is negatively correlated with Churn (longer stay = less likely to leave), while `MonthlyCharges` show a positive correlation with the probability of leaving.

> <img width="967" height="887" alt="image" src="https://github.com/user-attachments/assets/fafa8888-0bc9-4bf2-be58-f8b6718ac98e" />


---

## 📂 Project Structure & Workflow

1.  **Data Cleaning:** * Flattened complex JSON structures.
    * Converted `TotalCharges` to numeric and handled missing values.
    * Mapped categorical variables for better visualization.
2.  **Exploratory Data Analysis (EDA):**
    * Distribution analysis of Churn vs. Non-Churn.
    * Categorical analysis (Gender, Seniority, Partner, Dependents).
    * Service analysis (Phone, Multiple Lines, Internet, Tech Support).
3.  **Visualizations:**
    * Used Seaborn `countplot` for categorical drivers.
    * Used `kdeplot` and `histplot` to analyze numerical distributions of charges and tenure.

---

## 💡 Strategic Recommendations

* **Contract Conversion:** Create targeted marketing campaigns to move "Month-to-month" users into "One-year" contracts through small price incentives.
* **Fiber Optic Support:** Bundle Fiber Optic plans with **Premium Tech Support** at no extra cost for the first 3 months to reduce early frustration.
* **Automated Payments:** Offer a small "autopay discount" for customers who switch from Electronic Checks to Bank Transfers or Credit Cards.
* **New Customer Success:** Implement a "90-day check-in" program to provide extra support to new users during their highest-risk period.

---

*Created by*
<p>
<a href="https://github.com/melnotte" target="_blank">
<img src="https://avatars.githubusercontent.com/u/123502406?v=4" width="100px;" alt="Foto de [Tu Nombre]"/>
<br />
<sub><b>[Melanie Abigail Calderón Flores]</b></sub>
</a>
</p>
