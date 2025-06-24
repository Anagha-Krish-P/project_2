## PROJECT 2 
 1. Importing Libraries & Reading Data
    - Loaded Titanic dataset using Pandas
    - Used libraries for data analysis and visualization (NumPy, Matplotlib, Seaborn)
2. Initial Data Checks
    - Checked first and last rows, info, stats, shape, and missing values
3. Cleaned Column Names
    - Removed extra spaces or tabs from column names
4. Handled Missing Values
    - Filled missing Age with mean
    - Filled missing Cabin and Embarked with mode (most common value)
5. Label Encoding for Categorical Columns
    - Converted text columns to numbers using LabelEncoder
6. Data Normalization (Min-Max) & Standardization (Z-score)
    - MinMaxScaler: Scales all values between 0 and 1
    - StandardScaler: Transforms features to standard normal distribution
7. Histograms for Numerical Columns
    - Plotted histograms to see distribution of numeric columns
8. Boxplots for Outlier Detection
    - Used boxplots to detect outliers in Age and Fare
9. Handled Outliers using IQR
    - Used Interquartile Range (IQR) to detect outliers
    - Replaced those outliers with the mean of the column
10. Correlation Matrix (Heatmap)
    - Showed how features are related
    - Darker color = stronger relationship
11. Pairplot for Feature Relationships
    - Showed scatterplots between features
    - hue='Survived' helps us see how survival varies by other features
### SUMMARY

Cleaned and transformed the Titanic dataset → handled missing values and outliers → visualized data → understood feature relationships with correlation and pairplot




