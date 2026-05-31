# MSCS_634_Lab1


## Student Information
**Name:** Srujana Nevoji  
**Course:** MSCS 634 – Data Mining  
**Lab Title:** Lab 1 – Data Visualization, Preprocessing, and Statistical Analysis

## Purpose of the Lab

The purpose of this lab was to explore a real-world dataset using Python, Pandas, Matplotlib, and Jupyter Notebook. The lab focused on data visualization, data preprocessing, and statistical analysis techniques that are commonly used in data mining and data science projects.

## Dataset

The dataset used for this lab was **Sales_Data.csv**, obtained from Kaggle.

The dataset contains sales-related information including:
- Region
- Country
- Item Type
- Sales Channel
- Order Priority
- Order Date
- Units Sold
- Unit Selling Price
- Unit Making Cost

## Data Visualization

Several visualizations were created to better understand the dataset:

### Histogram
The histogram of Units Sold helped visualize how sales quantities are distributed throughout the dataset. Most records were concentrated within certain sales ranges, allowing patterns in sales volume to be observed. This type of visualization is useful for understanding whether the data is evenly distributed or skewed toward particular values.

### Bar Chart
The bar chart comparing Sales Channels showed the frequency of orders across different channels. This visualization made it easier to identify which sales channels were used most frequently and how customer purchasing behavior varied across channels.

### Box Plot
The box plot provided a clear view of the spread of Units Sold and highlighted potential outliers. Outliers can significantly affect statistical analysis, making it important to identify and investigate them before proceeding.
### Key Insights
- Units Sold showed variation across sales records.
- Different sales channels had different order frequencies.
- The box plot helped identify unusual sales values that may be considered outliers.

## Data Preprocessing

The following preprocessing techniques were applied:

### Missing Value Handling
The dataset was examined for missing values using the `isnull().sum()` function. Missing values can degrade analysis quality and lead to inaccurate conclusions. After checking the dataset, appropriate handling techniques were applied to ensure data completeness.

### Outlier Detection
The Interquartile Range (IQR) method was used to identify unusual observations in the Units Sold column. Outliers may represent data entry errors, exceptional business events, or rare observations. Detecting them helps improve the reliability of statistical analysis.

### Data Reduction
Data reduction techniques were applied to simplify the dataset while retaining important information. Sampling reduced the number of records analyzed, while removing unnecessary columns helped focus the analysis on the most relevant attributes.

### Scaling and Discretization
Min-Max Scaling was used to transform numerical values into a common range between 0 and 1. This helps ensure that variables with larger values do not dominate the analysis. Discretization grouped continuous sales values into categories such as Low, Medium, and High, making the data easier to interpret.

## Statistical Analysis

The following statistical techniques were performed:

### General Data Exploration
- `df.info()`
- `df.describe()`

### Central Tendency Measures
- Minimum
- Maximum
- Mean
- Median
- Mode

### Dispersion Measures
- Range
- Quartiles
- Interquartile Range (IQR)
- Variance
- Standard Deviation

### Correlation Analysis
A correlation matrix was generated to evaluate relationships among numerical variables.

## Challenges Faced
One challenge was learning how to use Jupyter Notebook and becoming familiar with its environment. Additional challenges included correctly loading the dataset, understanding preprocessing techniques, and performing statistical calculations. Organizing screenshots and preparing files for GitHub submission also required careful attention. Despite these challenges, the lab provided valuable hands-on experience with real-world data analysis.

## Conclusion

This lab provided hands-on experience with data mining concepts, including data exploration, visualization, preprocessing, and statistical analysis. The techniques learned in this lab will be useful for future data mining and machine learning projects.
