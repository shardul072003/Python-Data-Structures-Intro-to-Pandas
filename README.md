# Python Data Structures & Intro to Pandas 

##  Overview
This repository contains a Jupyter Notebook (`Assignment(2).ipynb`) that demonstrates foundational Python skills essential for data analysis. The exercises progress from built-in Python data structures to handling tabular data using industry-standard libraries like **NumPy** and **Pandas**. 

This project serves as a practical demonstration of data manipulation, cleaning, and basic exploratory data analysis (EDA) techniques.

##  Key Concepts Covered

The notebook is divided into several exercises targeting specific skills:

### 1. Core Python Data Structures
* **Lists:** Performing comprehensive operations including `append`, `extend`, `insert`, `remove`, `pop`, `sort`, and `reverse`.
* **Tuples:** Demonstrating the concept of immutability and data safety.
* **Sets:** Utilizing sets to automatically filter and remove duplicate values.
* **Dictionaries:** Creating key-value pairs, updating existing values, and appending new keys.

### 2. Control Flow & Logic
* **Conditional Statements (`if`, `elif`, `else`):**
  * Building a voting eligibility checker.
  * Creating a grading system based on numerical thresholds.
  * Using nested conditions to evaluate if a number is positive/negative/zero and even/odd.

### 3. Numerical Computing with NumPy
* Generating scalar, 1D, and 2D arrays.
* Utilizing `np.arange()` and `.reshape()` to structure matrices.
* Generating a 4x4 matrix of random integers using `np.random.randint()`.

### 4. Data Manipulation with Pandas
* Converting a 2D NumPy array into a structured Pandas DataFrame.
* **Data Cleaning & Exploration:**
  * Creating a custom DataFrame with mock employee data (Name, Age, City, Salary).
  * Exploring data distributions using `.info()` and `.describe()`.
  * Selecting and dropping specific columns.
  * **Imputation:** Handling missing data (`NaN`) by filling them with the column mean.
  * Identifying and removing duplicate records to ensure data integrity.

## 🛠️ Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Libraries:** `pandas`, `numpy`
