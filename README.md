# Uber-data-Analysis
Python

Insights we are going to Find
1. For how much miles mostly cabs are booked.
2. In which month Cabs bookings are very less.
3. What is main purpose of booking of cabs.
4. Which time in a day mostly cabs are booked.


Libraries Used:

Pandas:  This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.
Numpy: Numpy arrays are very fast and can perform large computations in a very short time.
Matplotlib / Seaborn: This library is used to draw visualizations.

 we can import the dataset using the pandas library.
 You can find uber dataset  in csv file in files.

 We need to find the null values.
 dataset.info() this command is mainly used to do that so.

 Data Preprocessing

 we will me filling the null values with a NOT keyword.
 dataset['PURPOSE'].fillna("NOT", inplace=True)

 We will convert our time into four categories to get proper insights if which time mostly cabs are booked.

  Then we must drop the null values which got in our new made columns.


  Data Visualization

  Thenw we will plot to see rides for category like buisness or personal
  or purpose of ride.
  

