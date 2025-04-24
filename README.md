# Titanic-survival-dataanalysis

Performed this task on kaggle: https://www.kaggle.com/code/sanchityyiuh/notebook431435950f
# Go Through:
1.import<br>
2.handling null: Age- int datatype so median<br>
                 Cabin- Object data type so used NaN<br>
                 Embarked- used mode for it<br>
3.Categorical to numerical: for Sex used 0:male 1:female<br>
                            for Embarked used pd.get_dummies() this creates a columns for each unique value in column <br>
4.Normalize/Standardize Numerical Features: To bring the all numerical value on same scale<br>
5.Visualizing and removing outliers: Used Boxplot to visualise<br>
                                     Used IQR method to detect and remove outliers<br>
# IQR 
IQR stands for Interquartile Range, a measure of statistical dispersion and a powerful tool for outlier detection.<br>
IQR = Q3 - Q1<br>
Q1 (25th percentile): Lower quartile – 25% of data lies below this value.<br>
Q3 (75th percentile): Upper quartile – 75% of data lies below this value.<br>
IQR is the range between these quartiles.<br>
<br>
(Additional) 6.Correlation and Linear regression model<br>

Created by Sanchit(Karlex)
