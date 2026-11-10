# Python Data Analytics Assignment 2 – Data Visualization

## Project Overview
This project focuses on data visualization using Python libraries such as Pandas, Matplotlib, and Seaborn. The Seaborn Taxis dataset is used to explore taxi trip information, handle missing values, and create different visualizations to identify patterns and relationships in the data.

## Dataset
- **Dataset:** Taxis
- **Source:** Seaborn built-in dataset
- **Loading method:** `sns.load_dataset("taxis")`

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning
- Identified missing values using `isnull()` and `sum()`.
- Filled missing payment values using mode imputation.
- Removed rows containing missing pickup and dropoff location information.
- Verified missing values after data cleaning.

## Visualizations

### Matplotlib / Pandas
1. **Line Chart:** Fare over time.
2. **Bar Chart:** Total fare by pickup borough.
3. **Pie Chart:** Distribution of trips by payment method.
4. **Histogram:** Distribution of taxi trip distances.
5. **Box Plot:** Distribution of tips by pickup borough.

### Seaborn
1. **Count Plot:** Number of trips by pickup borough.
2. **Scatter Plot:** Relationship between distance and fare.
3. **Heatmap:** Correlation between numerical variables.
4. **Pair Plot:** Pairwise relationships between distance, fare, tip, and total, categorized by pickup zone.
5. **Violin Plot:** Fare distribution by payment method.

## Key Learning Outcomes
- Loading and exploring datasets using Pandas and Seaborn.
- Identifying and handling missing values.
- Understanding categorical and numerical data.
- Creating different types of statistical visualizations.
- Analyzing relationships and correlations between variables.
- Customizing charts using Matplotlib and Seaborn.

## How to Run
1. Clone this repository.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn jupyter`

3. Open Jupyter Notebook:

   `jupyter notebook`

4. Open the assignment notebook and run the cells sequentially.

## Conclusion
This assignment provided practical experience in Python-based data visualization and exploratory data analysis (EDA). It helped develop an understanding of how visualizations can be used to explore datasets, identify patterns, and communicate insights effectively.
