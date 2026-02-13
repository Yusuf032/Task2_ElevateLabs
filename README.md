# Task2_ElevateLabs
# Exploratory Data Analysis (EDA) — Titanic Dataset

## 📌 Objective

The goal of this task is to understand the dataset using statistics and visualizations before applying any Machine Learning model.
EDA helps identify patterns, relationships, anomalies, and important features in the dataset.

---

## 🛠 Tools & Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

---

## 📂 Dataset

Titanic Dataset (CSV format)

The dataset contains passenger details such as:

* Age
* Gender
* Passenger Class
* Fare
* Embarked Location
* Survival Status

---

## 🔎 Steps Performed

### 1. Data Loading

* Imported dataset into Google Colab using Pandas
* Displayed first few rows using `head()`

### 2. Data Understanding

* Checked dataset shape
* Viewed column information
* Identified missing values
* Generated summary statistics

### 3. Data Cleaning

* Observed missing values in Age and Cabin columns
* Handled null values where necessary for visualization

### 4. Statistical Analysis

Calculated:

* Mean
* Median
* Standard Deviation
* Distribution of numerical features

### 5. Visualization

Performed multiple visualizations:

**Histograms**

* To understand feature distribution (Age, Fare)

**Boxplots**

* To detect outliers

**Correlation Heatmap**

* To identify relationships between features

**Pairplot**

* To understand survival patterns

**Interactive Plotly Graph**

* Age vs Fare survival relationship

---

## 📊 Key Observations

1. Females had a much higher survival rate than males.
2. First-class passengers survived more than lower-class passengers.
3. Children had better chances of survival.
4. Higher fare passengers were more likely to survive.
5. Fare column contains extreme outliers.
6. Survival is strongly related to Passenger Class and Gender.

---

## 🏁 Conclusion

EDA revealed that survival depends heavily on gender, passenger class, and fare.
Understanding these patterns is important before building predictive models.

---

## 👨‍💻 Author

Mohd Yusuf Khan
