# 🧠 Python Fundamentals Capstone Project

This project demonstrates data analysis and manipulation skills using **Python**, particularly with **Pandas** and **NumPy**. It simulates a real-world data processing scenario involving employees, projects, and performance evaluations.

---

## 📊 Datasets

The project uses three synthetic datasets:

- `employee.csv` – Contains ID, Name, Gender, City, and Age.
- `seniority.csv` – Contains ID and Designation Level.
- `project.csv` – Contains project assignments, costs, and statuses.

---

## ✅ Tasks Completed

### 1. Create DataFrames and Save as CSV
Initialized three DataFrames from predefined data and exported them as CSVs.

### 2. Handle Missing Values
Filled missing values in the project cost column using a **running average** with a `for` loop.

### 3. Split Full Name
Split the `Name` column into `First Name` and `Last Name`, removed the original column.

### 4. Merge All DataFrames
Joined all three DataFrames into one consolidated DataFrame called `Final`.

### 5. Calculate Bonus
Added a `Bonus` column:
- Employees with `Finished` projects received **5% of the project cost** as a bonus.

### 6. Handle Designation Changes
- Demoted employees by 1 level if any of their projects had `Failed` status.
- Removed any employees whose designation exceeded 4.

### 7. Format First Names
- Added `Mr.` or `Mrs.` as prefixes based on gender.
- Dropped the `Gender` column afterward.

### 8. Promote Senior Employees
Promoted employees aged over 29 by one designation level.

### 9. Summarize Project Costs
Created a new DataFrame `TotalProjCost` with:
- `ID`, `First Name`, and the total sum of their project costs.

### 10. Filter by City
Filtered and displayed all employees whose city names contain the letter **"o"**.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy

---
