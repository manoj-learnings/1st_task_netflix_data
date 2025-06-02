# 1st_task_netflix_data
Lets import all important lidraries to perform data cleaning and aslo the data set that was downloaded from kaggel 
Lets see the size of the dataset 
So there are total of 8807 rows and 12 columns
Lets Find out total null values for each column
We cant delete the rows with null values in director as it make us to delete huge ammount of data insteaded fill it with unknown same with cast,country
We has 10 null values in date_added but null values in release_year so we can just fill the null values with release year
Findout the unique values in rating
As 'TV-MA' is mode for rating fill null values with it
Now do the same thing for duration
AS it has large number of unique values it cant be filled with mode so just drop null values
Now lets findout the duplicates in the dataset
AS there are no duplicates in the data set no need to perform anything
Lets find out the data type of each column 
Lets convert the data type of date_added to Date time
