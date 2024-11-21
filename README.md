# Python for Data Science 

This repository contains notes, materials, and exercises for the **Python for Data Science** course. Each class covers foundational concepts and essential Python libraries for data science, progressively building skills for data processing and analysis. Assignments are organized by class in separate branches, and the status of each class’s exercises is indicated below.

## Classes Overview

### 1. **Class 1: Python Refresh** (25/09/24) - *Exercises DONE*
   - **Objective**: Refresh core Python programming skills.
   - **Topics**: Printing, variables, data types, lists, dictionaries, loops, and functions.
   - **Exercises**:
     - **Basic tasks**: Print a greeting, perform basic arithmetic, and manipulate strings.
     - **Data structures**: Practice with lists, dictionaries, tuples, and sets.
     - **Control flow**: Use if-statements, for and while loops, and Python 3.10’s `match` statement.
     - **Functions**: Define functions with and without parameters, utilize default parameters, and create a simple calculator.

### 2. **Class 2: Environments & Git** (02/10/24) - *Exercises DONE*
   - **Objective**: Set up and manage Python environments and introduce Git for version control.
   - **Topics**: Conda/venv environments, Git basics (commit, push, pull), and GitHub Desktop.
   - **Exercises**:
     - **Environment tasks**: Create and activate environments, install packages.
     - **Git tasks**: Practice Git commands and GitHub workflows.
     - **Python challenges**: Write functions like FizzBuzz, filter integers from lists, build a Celsius-to-Fahrenheit converter, and create a to-do list.

### 3. **Class 3: Object-Oriented Programming (OOP)** (09/10/24) - *Exercises DONE*
   - **Objective**: Learn OOP principles by building a course registration system.
   - **Topics**: Classes, methods, encapsulation, inheritance.
   - **Exercises**:
     - **Course & Student classes**: Define attributes and methods for managing courses and students.
     - **Registration system**: Implement a system to handle course enrollments and withdrawals.
     - **GPA calculator**: Extend the registration system with grading and GPA calculation.

### 4. **Class 4: Basic Libraries I** (16/10/24) - *Exercises DONE*
   - **Objective**: Use key libraries for data processing and file management.
   - **Topics**: Numpy, Scipy, Math, `os`, `glob`, and `shutil`.
   - **Exercises**:
     - **File management**: Count files in directories, check naming conventions.
     - **Data analysis**: Organize files by date, count annotations by month/year, identify the most active months.
     - **Advanced tasks**: Sort annotations from newest to oldest and count unique regions in satellite data.

### 5. **Class 5: Basic Libraries II** (21/10/24) - *Exercises DONE*
   - **Objective**: Extend data management skills with additional libraries and practice with large datasets.
   - **Topics**: Numpy, Scipy, Math, `os`, `glob`, `shutil`.
   - **Exercises**:
     - **Data organization**: Analyze annotations per month, save data in multiple formats (JSON, Pickle).
     - **Sorting and filtering**: Sort annotations chronologically for specified periods and count occurrences by region.

### 6. **Class 6: Pandas – Data Loading, Cleaning, and Exploration** (06/11/24) - *Exercises DONE*
   - **Objective**: Introduce data manipulation with Pandas, including data cleaning and transformation.
   - **Topics**: Loading datasets, handling missing data, filtering, and preprocessing.
   - **Exercises**:
     - **Pandas I**: Basic data cleaning exercises, such as counting and filling missing values, filtering for specific content types, and creating derived columns.
     - **Pandas II (Titanic)**: Count and fill missing values, calculate average fares, and create a `FamilySize` column by summing `SibSp` and `Parch`.
     - **Pandas III (Netflix & Titanic)**:
       - **Netflix**: Identify missing ratings, count films by country, and find the year with the most releases.
       - **Titanic**: Calculate survival percentages by gender and class.

### 7. **Class 7: Datasets Pandas II**  (13/11/24) - *Exercises DONE*
   - **Objective**: Deepen understanding of data manipulation using Pandas, with a focus on advanced transformations, handling missing data, and creating reusable workflows.
   - **Topics**: Lambda and map functions, advanced data manipulation, handling missing data, and transformations.
   - **Exercises**:
     - **Advanced Data Manipulation**:
       - Use a **lambda** function to classify flowers by petal length (`short` for less than 3 cm, `long` otherwise).
       - Map the `Species` column to numeric values (`Iris-setosa`: 0, `Iris-versicolor`: 1, `Iris-virginica`: 2).
       - Count occurrences in the `Species` column using `value_counts`.
       - Remove duplicate rows based on `SepalLengthCm` and `PetalLengthCm`.
       - Convert `SepalLengthCm` to a string, then back to a float, handling errors gracefully.
       - Save the modified dataset to a CSV file with the index included.
     - **Handling Missing Data and Transformations**:
       - Count missing values in each column.
       - Replace missing values in the `department` column with `"Unknown"`.
       - Fill missing `age` values with the column's average.
       - Drop rows where the `professor` column is missing.
       - Create a new column, `professor_last_name`, by extracting the last name from the `professor` column.
       
### 8. **Class 8: Matplotlib and Seaborn – Data Visualization** (20/11/24) - *Exercises DONE*
   - **Objective**: Introduce data visualization using Matplotlib and Seaborn, focusing on advanced plotting techniques and customization.
   - **Topics**: Matplotlib and Seaborn integration, exploratory data visualization, and plot styling.
   - **Exercises**:
     - **Matplotlib**:
       - Plot the number of students in the top 5 universities for Executive Education (2024), using university colors and adding title, xlabel, ylabel, and legend.
     - **Seaborn**:
       - Lineplot: Study Time by Student Name, identifying the highest study time.
       - Histplot: Grade distribution, determining the most frequent grade range.
       - ECDF Plot: Percentage of students scoring less than 85.
       - Stripplot: Grade distribution by Course, finding the course with the most spread.
       - Swarmplot: Study Time by Gender, identifying the gender with higher average study time.
       - Pointplot: Average Grade by Course, finding the course with the highest average grade.

### 9. Class 9: *PENDING*

## Instructions for Executing the Code

  Environment Setup: Ensure Python 3.10 is installed along with necessary packages like Pandas, Numpy, Scipy, and Matplotlib:
     pip install pandas numpy scipy matplotlib

## Author

**Harshita Chivukula** - [GitHub Profile](https://github.com/harshita-chivukula)
