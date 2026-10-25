# Student Performance - Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a student performance dataset using Python. It focuses on understanding the dataset, cleaning the data, calculating descriptive statistics, identifying potential outliers, and exporting the cleaned dataset.

## Objectives
- Inspect the dataset structure and summary statistics.
- Check for missing values and duplicate records.
- Clean categorical data.
- Calculate statistical measures for student scores.
- Calculate total marks and percentage.
- Detect potential outliers using the IQR method.
- Export the processed dataset to a CSV file.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The project uses the `StudentsPerformance - StudentsPerformance.csv` dataset.

The dataset contains student information and scores in:
- Math
- Reading
- Writing

Other categorical columns include gender, race/ethnicity, parental level of education, lunch, and test preparation course.

## Project Workflow
1. Import the required Python libraries.
2. Load the dataset.
3. Display the first few rows and inspect the dataset.
4. Check missing values and duplicates.
5. Clean categorical columns by removing extra spaces and converting text to lowercase.
6. Calculate mean, median, standard deviation, and quartiles.
7. Calculate total marks and percentage.
8. Identify potential outliers using the Interquartile Range (IQR) method.
9. Export the processed dataset to a CSV file.

## Calculations

### Total Marks
Total Marks = Math Score + Reading Score + Writing Score

### Percentage
Percentage = (Total Marks / 300) × 100

### Outlier Detection Using IQR
- IQR = Q3 − Q1
- Lower Bound = Q1 − 1.5 × IQR
- Upper Bound = Q3 + 1.5 × IQR

Values below the lower bound or above the upper bound are identified as potential outliers.

## Output
The processed dataset is saved as:

`Student_Performance_Cleaned.csv`

## How to Run the Project
1. Download the project files.
2. Keep the source CSV dataset in the correct folder.
3. Open `EDA_Task7.ipynb` using Jupyter Notebook or Google Colab.
4. Update the dataset file path if necessary.
5. Run all notebook cells in order.
6. Check the output CSV file in the working directory.

## Project Structure

```text
Student-Performance-EDA/
│
├── EDA_Task7.ipynb
├── StudentsPerformance - StudentsPerformance.csv
├── Student_Performance_Cleaned.csv
└── README.md
```

## Conclusion
This project demonstrates the basic steps of Exploratory Data Analysis using Python. It helps summarize student scores, calculate overall performance, identify potential outliers, and prepare the dataset for further analysis.
