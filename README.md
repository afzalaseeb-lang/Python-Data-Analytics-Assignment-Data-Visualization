# Python-Data-Analytics-Assignment-Data-Visualization
Python Data Analytics Assignment 2 focusing on data visualization using Matplotlib, Pandas, and Seaborn. Includes data cleaning, handling missing values, and creating various visualizations using the Seaborn Taxis dataset to explore taxi trip patterns, fare distributions, and correlations.
# Python Data Analytics – Assignment 2: Data Visualization

## Project Overview

This project focuses on data cleaning, exploratory data analysis, and data visualization using Python libraries. The Seaborn Taxis dataset is used to explore taxi trip patterns, fare distributions, payment methods, and relationships between numerical variables.

The assignment demonstrates how different visualization techniques can help identify patterns, trends, distributions, and correlations in real-world datasets.

## Dataset

- **Dataset Name:** Taxis Dataset
- **Source:** Seaborn Built-in Dataset
- **Loading Method:** `sns.load_dataset("taxis")`

The dataset contains information about taxi trips, including pickup and drop-off timestamps, passengers, distance, fare, tips, tolls, payment methods, and pickup/drop-off locations.

## Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Tasks Performed

### 1. Loading the Dataset
- Imported the Seaborn library.
- Loaded the built-in Taxis dataset into a Pandas DataFrame.

### 2. Handling Missing Values
- Identified missing values in the dataset.
- Checked column data types.
- Applied appropriate imputation techniques using median and mode.
- Removed rows containing missing values in critical columns.
- Verified the cleaned dataset.

### 3. Visualizations Using Matplotlib / Pandas

**Line Chart**
- Visualized daily average taxi fare over time using pickup timestamps.

**Bar Chart**
- Compared total taxi fares across different pickup boroughs.

**Pie Chart**
- Visualized the distribution of taxi trips by payment method.

**Histogram**
- Examined the distribution of taxi trip distances.

**Box Plot**
- Compared tip amount distributions across pickup boroughs.

### 4. Visualizations Using Seaborn

**Count Plot**
- Visualized the number of taxi trips in each pickup borough.

**Scatter Plot**
- Examined the relationship between trip distance and fare.
- Differentiated observations using pickup borough.

**Heatmap**
- Visualized correlations between distance, fare, tip, tolls, and total.

**Pair Plot**
- Explored pairwise relationships between distance, fare, tip, and total.
- Compared observations across pickup zones.

**Violin Plot**
- Examined fare distributions across different payment methods.

## Key Learning Outcomes

- Understanding data cleaning and missing-value handling.
- Working with Pandas DataFrames.
- Creating different types of charts using Matplotlib.
- Performing statistical data visualization using Seaborn.
- Understanding correlation and relationships between numerical variables.
- Identifying distributions, trends, and outliers.
- Interpreting visualizations and extracting meaningful insights.

## Conclusion

This assignment provided practical experience in data visualization using Python. By applying Matplotlib and Seaborn techniques to the Taxis dataset, different aspects of taxi trip behaviour, fare distribution, payment preferences, and numerical relationships were explored.

The project strengthened my understanding of exploratory data analysis and the importance of visualizing data to communicate meaningful insights.

---
Tools: Python | Pandas | NumPy | Matplotlib | Seaborn
Environment: Google Colab
