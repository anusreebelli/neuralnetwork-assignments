Spring 2024: CS5720: Neural Network Deep Learning: In Class Programming Assignment-3
Name: Belli Anusha Sree ID: 700758644
1.1. Create a class Employee and then do the following
• Create a data member to count the number of Employees
• Create a constructor to initialize name, family, salary, department
• Create a function to average salary
• Create a Fulltime Employee class and it should inherit the properties of Employee class
• Create the instances of Fulltime Employee class and Employee class and call their member functions

2. Numpy
Using NumPy create random vector of size 20 having only float in the range 1-20.
Then reshape the array to 4 by 5
Then replace the max in each row by 0 (axis=1)
(you can NOT implement it via for loop)

Code File - ICP_3_Spring24.ipynb  Document- ICP_3_Spring24.DOCX


Assignment-4
1. Data Manipulation
a. Read the provided CSV file ‘data.csv’.
b. https://drive.google.com/drive/folders/1h8C3mLsso-R-sIOLsvoYwPLzy2fJ4IOF?usp=sharing
c. Show the basic statistical description about the data.
d. Check if the data has null values.
i. Replace the null values with the mean
e. Select at least two columns and aggregate the data using: min, max, count, mean.
f. Filter the data frame to select the rows with calories values between 500 and 1000.
g. Filter the data frame to select the rows with calories values > 500 and pulse < 100.
h. Create a new “df_modified” data frame that contains all the columns from df except for
“Maxpulse”.
i. Delete the “Maxpulse” column from the main df data frame
j. Convert the datatype of Calories column to int datatype.
k. Using pandas create a scatter plot for the two columns (Duration and Calories).

2. Linear Regression
a) Import the given “Salary_Data.csv”
b) Split the data in train_test partitions, such that 1/3 of the data is reserved as test subset.
c) Train and predict the model.
d) Calculate the mean_squared error
e) Visualize both train and test data using scatter plot.
   CODE:nndl_assignment4_spring.ipynb


