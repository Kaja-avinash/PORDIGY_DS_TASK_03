# 🚢 Titanic Survivors Analysis: An Exploratory Data Study

## 📌 Project Overview
This project presents an exploratory analysis of the Titanic dataset as part of the Prodigy Data Science Internship. It focuses on uncovering survival patterns based on passenger demographics, ticket class, and other onboard attributes through data preprocessing, visualization, and statistical interpretation.

---

## 🧠 Objective
- Clean and prepare the Titanic dataset for analysis.
- Explore relationships between passenger features and survival rates.
- Derive insights using visualizations and correlation metrics.

---

## 📂 Dataset Summary
The dataset includes comprehensive information about passengers aboard the RMS Titanic, including:
- `PassengerId`: Unique ID for each passenger.
- `Survived`: Binary indicator of survival (0 = No, 1 = Yes).
- `Pclass`: Ticket class (1st, 2nd, or 3rd).
- `Name`, `Sex`, `Age`: Personal information.
- `SibSp`, `Parch`: Family aboard indicators.
- `Fare`: Ticket cost.
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

---

## 🛠️ Tools & Technologies Used
- **Python**  
- **Pandas** – for data wrangling  
- **NumPy** – for numerical processing  
- **Matplotlib & Seaborn** – for data visualization  
- **Jupyter Notebook** – for interactive development  

---

## 🔍 Key Steps in the Analysis

### ✅ Data Cleaning
- Removed the `Cabin` column due to excessive missing values.
- Filled missing `Age` values with the mean age.
- Imputed missing `Embarked` values with the mode.

### 📊 Exploratory Data Analysis (EDA)
- Bar plots for gender-wise and class-wise survival analysis.
- Age distribution visualization with histograms.
- Correlation heatmap to study feature relationships.

---

## 📈 Key Insights
- **Gender Bias in Survival**: Females had significantly higher survival rates.
- **Class Advantage**: Passengers in 1st class were more likely to survive than those in 2nd or 3rd.
- **Age Factor**: Younger children had higher chances of survival, indicating possible prioritization.
- **Fare Correlation**: Higher fares correlated with better survival odds.

---

## 🎯 Conclusion
This analysis of the Titanic dataset demonstrates how structured preprocessing and insightful visualizations can uncover meaningful trends in real-world data. The project reinforces the value of EDA in interpreting complex datasets and supports evidence-based conclusions about historical events.

---

## 📁 Project Structure
├── Titanic_EDA.ipynb # Jupyter Notebook containing the full analysis
├── titanic.csv # Dataset file
├── visuals/ # Charts and heatmaps generated
└── README.md # Project documentation

---

## 👤 Author
**K. Avinash**  
B.Tech - Artificial Intelligence & Data Science  
Vasireddy Venkatadri Institute of Technology  

---

## 📬 Contact
- 📧 Email: avinashkaja280@gmail.com  
- 💼 LinkedIn: [Avinash Kaja](https://www.linkedin.com/in/avinash-kaja)  

---

⭐ *If you found this project insightful, feel free to star it or reach out for collaboration!*
