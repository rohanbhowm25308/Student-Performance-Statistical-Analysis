#  Student Performance Statistical Analysis

> **Turning student data into meaningful statistical insights.**

A complete **Data Science with Python** project that explores student performance using **Exploratory Data Analysis (EDA), descriptive statistics, hypothesis testing, confidence intervals, and effect-size analysis**.

The project investigates how factors such as **test preparation and parental education** relate to academic performance and whether test preparation is associated with student pass/fail status.

---

##  Live Demo

🚀 **Live Demo / Project Notebook:**  
https://github.com/rohanbhowm25308/Student-Performance-Statistical-Analysis

> The complete project, dataset, and Jupyter Notebook are available in this GitHub repository.

---

##  Project Overview

Student performance is influenced by several academic and demographic factors. Instead of relying only on averages and visualizations, this project applies statistical methods to determine whether observed patterns are statistically meaningful.

The analysis answers three core questions:

*  Does test preparation relate to students' average scores?
*  Does parental education relate to differences in student performance?
*  Is test preparation associated with student pass/fail status?

The project combines **visual analysis with statistical evidence** to provide a structured view of student performance.

---

## ✨ Key Features

*  Dataset quality and consistency checks
*  Exploratory Data Analysis
*  Score distribution analysis
*  Correlation analysis
*  Descriptive statistics
*  Independent Samples Welch's t-Test
*  One-Way ANOVA
*  Chi-Square Test of Independence
*  Cohen's d effect size
*  Eta-squared effect size
*  Cramér's V
*  95% Confidence Intervals
*  Statistical Results Dashboard
*  Interpretation and limitations
*  Reproducible Python workflow

---

##  Statistical Methods

### 1. Independent Samples t-Test

Used to compare the average scores of students who **completed test preparation** with those who **did not**.

**Measures:**

* Mean difference
* Welch's t-statistic
* p-value
* 95% confidence interval
* Cohen's d

---

### 2. One-Way ANOVA

Used to examine whether average student scores differ across **parental education levels**.

**Measures:**

* F-statistic
* p-value
* Eta-squared
* Tukey HSD post-hoc analysis when applicable

---

### 3. Chi-Square Test of Independence

Used to examine the relationship between **test preparation status** and **pass/fail status**.

**Measures:**

* Chi-square statistic
* Degrees of freedom
* p-value
* Expected frequencies
* Cramér's V

---

##  Exploratory Analysis

The notebook includes visualizations such as:

* Average score distribution
* Average score by test-preparation status
* Average score by parental education
* Numerical correlation heatmap

These visualizations help identify patterns before formal statistical testing.

---

## 🗃️ Dataset

The dataset contains **1,200 student records** with academic, demographic, and behavioral attributes.

### Main Features

| Feature                      | Description                   |
| ---------------------------- | ----------------------------- |
| `student_id`                 | Unique student identifier     |
| `gender`                     | Student gender                |
| `age`                        | Student age                   |
| `school`                     | School category               |
| `address`                    | Urban/rural location          |
| `parental_education`         | Parent education level        |
| `study_time`                 | Weekly study-time category    |
| `test_preparation`           | Test preparation status       |
| `internet_access`            | Internet availability         |
| `family_support`             | Family academic support       |
| `extracurricular_activities` | Extracurricular participation |
| `lunch_type`                 | Lunch category                |
| `absences`                   | Number of absences            |
| `math_score`                 | Mathematics score             |
| `reading_score`              | Reading score                 |
| `writing_score`              | Writing score                 |
| `average_score`              | Mean subject score            |
| `pass_status`                | Pass/Fail classification      |

> **Dataset Note:** The dataset is self-generated for statistical-learning and project purposes. It should not be interpreted as a representative real-world school population.

---

##  Technologies Used

```text
Python
Pandas
NumPy
SciPy
Statsmodels
Matplotlib
Seaborn
Jupyter Notebook
```

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/rohanbhowm25308/Student-Performance-Statistical-Analysis.git
```

### 2. Open the project

```bash
cd Student-Performance-Statistical-Analysis
```

### 3. Install dependencies

```bash
pip install pandas numpy scipy statsmodels matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Student_Performance_Insights_Statistical_Analysis.ipynb
```

Make sure the CSV file remains in the same directory as the notebook.

---

##  Statistical Decision Rule

The project uses:

```text
Significance Level (α) = 0.05
Confidence Level = 95%
```

General interpretation:

```text
p-value < 0.05  →  Statistically significant
p-value ≥ 0.05  →  Not statistically significant
```

Statistical significance is interpreted together with **effect sizes and confidence intervals** rather than using p-values alone.

---

##  What This Project Demonstrates

This project demonstrates practical understanding of:

* Data cleaning and validation
* Exploratory Data Analysis
* Statistical reasoning
* Hypothesis formulation
* Statistical testing
* Confidence intervals
* Effect-size interpretation
* Data visualization
* Reproducible analysis
* Communicating statistical findings

---

##  Limitations

* The dataset is self-generated for learning and demonstration.
* The observations should not be treated as a real representative student population.
* Statistical association does not establish causation.
* Multiple statistical tests can increase the possibility of false-positive findings.
* The pass threshold used in the project is a defined analytical threshold.

---

## 👨‍💻 Author

**Rohan Bhowmik**

> Aspiring AI/ML , Data Science & Web Developer

**Focus Areas:**
`Artificial Intelligence` • `Machine Learning` • `Data Science` • `Python` • `Web Developer`

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐.

**Developed by Rohan Bhowmik**

**Built with Python • Statistics • Data Science**
