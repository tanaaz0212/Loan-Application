# Loan-Application
#  Loan Application Data Analysis

##  Project Overview

This project analyzes loan application data to understand customer behavior, default risk, and financial patterns using basic statistics, probability, and linear algebra concepts in Python.

---

##  Objectives

* Analyze income and loan distribution
* Calculate statistical measures (mean, median, variance, etc.)
* Estimate probability of loan default
* Study relationship between credit score and default
* Understand data distribution using skewness, kurtosis, and Q-Q plots
* Apply vector operations for customer comparison

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy

---

##  Dataset

* File: `loan_applications.csv`
* Contains:

  * Income
  * Loan Amount
  * Credit Score
  * Default Status

---

##  Steps Performed

### 1. Descriptive Statistics

* Mean, Median, Mode of Income
* Range, Variance, Standard Deviation of Loan Amount

### 2. Probability Analysis

* Overall probability of default
* Conditional probability based on credit score
* Credit score categorization

### 3. Distribution Analysis

* Histogram plots
* Gaussian (Normal) distribution comparison
* Skewness and Kurtosis
* Q-Q Plot for normality check

### 4. Linear Algebra

* Represent customers as vectors (Income, Loan Amount)
* Dot product calculation
* Vector magnitude (norm)
* Angle between vectors
* Vector visualization

---

##  Key Insights

* Income distribution helps understand customer earning patterns
* Higher credit scores generally show lower default probability
* Skewness indicates whether loan data is balanced or not
* Kurtosis shows presence of outliers
* Vector analysis helps compare customers mathematically

---

##  How to Run

1. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib scipy
   ```

2. Place `loan_applications.csv` in the same folder

3. Run the script:

   ```bash
   python your_script_name.py
   ```

---

##  Conclusion

This project demonstrates how statistical and mathematical techniques can be applied to real-world financial data to extract meaningful insights and support decision-making.


