# data-cleaning-preprocessing-task
#Titanic Dataset Preprocessing
#The following steps were carried out:

1. Data Import & Exploration  
   - Loaded the dataset using 'pandas'  
   - Inspected column names, data types, and basic statistics

2. Handling Missing Values
   - Filled missing values in numerical columns using mean or median
   - Imputed missing values in categorical columns with the most frequent category

3. Encoding Categorical Variables
   - Converted 'sex' and 'embarked' columns into numerical format using Label Encoding

4. Feature Scaling
   - Applied normalization to numerical features like 'age' and 'fare' to ensure uniform scale

5. visualising Outlier & Removal
   - Used boxplots to visualize outliers in numerical data  
   - Removed outliers using the Interquartile Range (IQR) method
