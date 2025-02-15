# PLP-Week-7-Data-Analysis-and-Techniques

# Data Analysis and Visualization with Pandas and Matplotlib

## Overview
This project involves analyzing a dataset using the Pandas library in Python and visualizing the results using Matplotlib and Seaborn. The dataset chosen for analysis is the Iris dataset, which is a well-known dataset in machine learning.

## Objectives
- Load and explore the dataset using Pandas.
- Perform basic data analysis to compute summary statistics.
- Create visualizations to understand patterns and trends in the data.

## Tasks Performed

### Task 1: Load and Explore the Dataset
- Loaded the Iris dataset using `sklearn.datasets.load_iris()`.
- Converted the dataset into a Pandas DataFrame and displayed the first few rows.
- Checked for missing values and verified data types.

### Task 2: Basic Data Analysis
- Computed descriptive statistics using `.describe()`.
- Grouped data by species and computed mean values for numerical columns.

### Task 3: Data Visualization
Four different types of visualizations were created:

1. **Line Chart** - Visualized the trend of sepal length.
2. **Bar Chart** - Compared the average petal length per species.
3. **Histogram** - Displayed the distribution of sepal width.
4. **Scatter Plot** - Showed the relationship between sepal length and petal length.

All visualizations were customized with appropriate titles, axis labels, and legends.

## Findings
- The **Setosa** species has the smallest petal length on average.
- The **scatter plot** indicates a clear separation between species based on sepal and petal length.
- The **histogram** suggests that most sepal width values are clustered around 3 cm.

## Dependencies
Ensure you have the following Python libraries installed before running the script:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## How to Run the Script
1. Clone the repository:
   ```bash
   git clone https://github.com/PatelFamily21/PLP-Week-7-Data-Analysis-and-Techniques.git
   ```
2. Navigate to the project directory:
   ```bash
   cd PLP-Week-7-Data-Analysis-and-Techniques
   ```
3. Run the script:
   ```bash
   python analyze_pandas_matplotlib.py
   ```

## Conclusion
This project demonstrates how to analyze a dataset using Pandas and visualize the results using Matplotlib and Seaborn. The findings highlight key insights derived from the Iris dataset.
