# Python for Data Science Class 7

This branch contains the notes and exercises for the class, focusing on **Pandas** for advanced data manipulation, handling missing data, and data transformations. The session builds on foundational Pandas concepts to introduce intermediate techniques for dataset preprocessing and analysis.

## Outline: Using Pandas

1. **Lambda and Map**  
   Applying lambda functions and mapping transformations to columns and series.
   
2. **Series**  
   Advanced operations and transformations on Pandas Series.
   
3. **Advanced Data Manipulation**  
   Techniques to reshape and preprocess datasets.
   
4. **Handling Missing Data and Data Transformation**  
   Methods for dealing with missing values and transforming data into usable formats.

## Exercises

- Create a **lambda** function to classify flowers based on their petal length.
- Use **map** to convert the `Species` column into numeric values:
- Use **value_counts** on the `Species` column to count how many entries belong to each species.
- Use **drop_duplicates** to remove any duplicate rows based on `SepalLengthCm` and `PetalLengthCm`.
- Use **astype** to convert the `SepalLengthCm` column to a string type, then back to a float type. Gracefully handle any errors during the conversion.
- Save the modified DataFrame to a CSV file using **to_csv**, ensuring the index is included.
- Count the number of missing values in each column.
- Replace missing values in the `department` column with "Unknown".
- Use **fillna** to fill missing values in the `age` column with the average age.
- Drop rows where the `professor` column is missing.
- Create a new column called `professor_last_name` by extracting the last name from the `professor` column.

## Requirements

To run these exercises, ensure you have the following:
- **Python 3.10** or later
- Libraries: Pandas, NumPy
- Environment: Jupyter Notebook, VS Code, or any IDE supporting Python notebooks

## Author

Harshita Chivukula - [GitHub Profile](https://github.com/harshita-chivukula)