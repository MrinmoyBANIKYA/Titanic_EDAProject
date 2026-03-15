# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the factors that influenced passenger survival during the Titanic disaster.

The goal of this project is to explore patterns in passenger demographics, travel class, and family structure to understand how these variables affected survival outcomes.

This project demonstrates fundamental **data analytics skills**, including:

- Data cleaning
- Exploratory data analysis
- Data visualization
- Feature engineering
- Insight extraction

---

# 📊 Dataset Information

The dataset used in this project is the **Titanic dataset**, widely used for data science practice and machine learning problems.

### Dataset Files

| File | Description |
|-----|-------------|
| `train.csv` | Training dataset containing passenger information and survival labels |
| `test.csv` | Test dataset containing passenger features without survival labels |

---

# 📂 Project Structure

```
titanic-eda-analysis
│
├── data
│   ├── train.csv
│   └── test.csv
│
├── notebooks
│   └── titanic_eda.ipynb
│
├── images
│
├── requirements.txt
└── README.md
```

---

# 🛠️ Tools and Technologies Used

### Programming Language
- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

These tools were used for **data manipulation, visualization, and exploratory analysis**.

---

# 🔍 Exploratory Data Analysis

The analysis is divided into multiple stages to systematically explore the dataset.

---

# 📈 Univariate Analysis

Univariate analysis focuses on examining the **distribution of individual variables**.

The following variables were analyzed:

- Age
- Fare
- Passenger Class (Pclass)
- Survival Distribution
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Gender (Sex)
- Port of Embarkation (Embarked)

This analysis helps identify:

- Data distribution
- Outliers
- Missing values
- Skewness

---

# 🔗 Bivariate Analysis

Bivariate analysis explores relationships between variables.

Key relationships analyzed include:

- Survival vs Gender
- Survival vs Passenger Class
- Survival vs Age
- Survival vs Fare
- Survival vs Family Size

This helps identify which variables strongly influenced survival probability.

---

# ⚙️ Feature Engineering

Several new features were created to improve the analysis.

### 1. Fare Grouping

Ticket fare was categorized into groups to analyze survival patterns based on economic class.

---

### 2. Family Size

Family size was calculated using:

```
Family Size = SibSp + Parch + 1
```

This helps determine whether passengers traveling **alone or with family members** had different survival outcomes.

---

### 3. Family Type

Passengers were categorized based on family size:

- Alone
- Small Family
- Medium Family
- Large Family

This helps analyze survival probability based on family structure.

---

### 4. Deck Extraction

Deck information was extracted from the **Cabin column**, which may indicate passenger location on the ship and potential survival advantage.

---

# 📊 Key Insights

### 1. Gender strongly influenced survival
Female passengers had significantly **higher survival rates** compared to male passengers.

### 2. Passenger class affected survival
Passengers in **first class had higher survival probability** compared to passengers in second and third classes.

### 3. Family structure influenced survival
Passengers traveling in **small families had better survival outcomes** compared to passengers traveling alone or in very large groups.

### 4. Fare correlated with survival
Passengers who paid **higher ticket fares generally had better survival chances**, likely due to higher travel classes.

---

# 📷 Visualizations

Below are some important visualizations used in the analysis.

*(Paste your generated plots inside the `images` folder and link them here.)*

---

## Age Distribution

![Age Distribution](C:\Users\mrinm\OneDrive\Desktop\EDACampusX\images)

---

## Fare Distribution

![Fare Distribution](C:\Users\mrinm\OneDrive\Desktop\EDACampusX\images)

---

## Survival Distribution

![Survival Count](C:\Users\mrinm\OneDrive\Desktop\EDACampusX\images)

---

## Survival vs Gender

![Survival vs Gender](C:\Users\mrinm\OneDrive\Desktop\EDACampusX\images)

---

## Survival vs Passenger Class

![Survival vs Passenger Class](C:\Users\mrinm\OneDrive\Desktop\EDACampusX\images)

---

## Family Size Analysis

![Family Size](C:\Users\mrinm\OneDrive\Desktop\EDACampusX\images)

---

# ▶️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/titanic-eda-analysis.git
```

### 2. Navigate to the project folder

```
cd titanic-eda-analysis
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```
jupyter notebook
```

Open:

```
notebooks/titanic_eda.ipynb
```

---

# 🎯 Skills Demonstrated

This project demonstrates the following data analytics skills:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Statistical Interpretation
- Python Data Analysis Workflow

---

# 👨‍💻 Author

**Mrinmoy Banikya**

Computer Science Engineering Student  
Interested in Data Analytics, AI, and Data-Driven Business Strategy.

---

⭐ If you found this project useful, consider giving it a **star on GitHub**.