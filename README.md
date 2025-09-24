# machine-learning-zoomcamp-homework1

Q1. Pandas version
What's the version of Pandas that you installed?

Answer - 2.3.2

Q2. Records count
How many records are in the dataset?

Answer - 9704

Q3. Fuel types
How many fuel types are presented in the dataset?

Answer - 2

Q4. Missing values
How many columns in the dataset have missing values?

Answer - 4

Q5. Max fuel efficiency
What's the maximum fuel efficiency of cars from Asia?

Answer - 23.75

Q6. Median value of horsepower
Find the median value of horsepower column in the dataset.
Next, calculate the most frequent value of the same horsepower column.
Use fillna method to fill the missing values in horsepower column with the most frequent value from the previous step.
Now, calculate the median value of horsepower once again.
Has it changed?

Answer - No

Q7. Sum of weights
Select all the cars from Asia
Select only columns vehicle_weight and model_year
Select the first 7 values
Get the underlying NumPy array. Let's call it X.
Compute matrix-matrix multiplication between the transpose of X and X. To get the transpose, use X.T. Let's call the result XTX.
Invert XTX.
Create an array y with values [1100, 1300, 800, 900, 1000, 1100, 1200].
Multiply the inverse of XTX with the transpose of X, and then multiply the result by y. Call the result w.
What's the sum of all the elements of the result?
Answer - 0.51
