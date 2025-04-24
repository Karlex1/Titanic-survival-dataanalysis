# Titanic-survival-dataanalysis

Performed this task on kaggle: https://www.kaggle.com/code/sanchityyiuh/notebook431435950f
# Go Through:
1.import
2.handling null: Age- int datatype so median
                 Cabin- Object data type so used NaN
                 Embarked- used mode for it
3.Categorical to numerical: for Sex used 0:male 1:female
                            for Embarked used pd.get_dummies() this creates a columns for each unique value in column 
4.Normalize/Standardize Numerical Features: To bring the all numerical value on same scale
5.Visualizing and removing outliers: Used Boxplot to visualise
                                     Used IQR method to detect and remove outliers
# IQR 
IQR stands for Interquartile Range, a measure of statistical dispersion and a powerful tool for outlier detection.
IQR = Q3 - Q1
Q1 (25th percentile): Lower quartile – 25% of data lies below this value.
Q3 (75th percentile): Upper quartile – 75% of data lies below this value.
IQR is the range between these quartiles.

(Additional) 6.Correlation and Linear regression model
