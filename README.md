# Unemployment-Analysis
Certainly! The provided Python code performs the following tasks:

Library Import:

The necessary libraries are imported, including Pandas for data manipulation, NumPy for numerical operations, and Matplotlib/Seaborn for data visualization.
Data Loading:

Two CSV files (Unemployment in India.csv and Unemployment_Rate_upto_11_2020.csv) are loaded into Pandas DataFrames (df1 and df2).
Column Name Cleanup:

Leading whitespaces in the column names of both DataFrames are removed to ensure consistency.
Merge DataFrames:

The two DataFrames are merged on the 'Date' column using an inner join, resulting in a new DataFrame called merged_df.
Data Type Check:

The data types of columns in the merged DataFrame are printed to verify correct types.
Data Conversion:

Columns related to unemployment rates are converted to numeric types. Any conversion errors are coerced to NaN.
Combine Columns:

The script combines two separate columns related to unemployment rates into a single column, prioritizing values from the first column when there are NaN values.
Column Cleanup:

The original separate columns are dropped from the DataFrame, as they are no longer needed.
NaN Value Removal:

Rows with NaN values in the combined 'Estimated Unemployment Rate (%)' column are removed from the DataFrame.
Data Visualization:

Seaborn is used to create a line plot of the estimated unemployment rate over time. The plot is customized with appropriate labels, title, and formatting for better presentation.
Plot Display:

The final plot is displayed using plt.show().
This code essentially prepares and merges two datasets related to unemployment rates, cleans up the data, and visualizes the estimated unemployment rate trends over time. The use of popular data manipulation and visualization libraries makes the code concise and efficient.





