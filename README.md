# Int1

Use Google Colab to run the given python code.

1. First import the Titanic Dataset from Kaggle.
2. Then preprocess the data using Panda library.
   a. Load the dataset
   b. Analyse the datashape, datatype and NaN values
3. Handle the missing values by
   a. adding mean values of column in place od missing numerical value.
   b. assigning 'Unknown' to categorical missing value, though it is mostly a redundant data, we will drop these specific rows and columns.
4. Then we encode the dataset which includes
   a. extracting titles from the names.
   b. Dropping unnecessary columns and rows
   c. Label encoding "SEX" and Hot encoding "TITLE" and "EMBARKED" columns
5. Normalising the dataset using MINMAX Scaler
6. Removing Outliers which results in reduction of 566 rows.
