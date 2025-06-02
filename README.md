# 1st_task_netflix_data
We began the data cleaning process by importing all the necessary libraries and loading the dataset downloaded from Kaggle. The dataset consists of 8,807 rows and 12 columns.

We first checked for missing values in each column. Some columns, such as director, cast, and country, had a significant number of missing values. Since dropping these rows would result in a large loss of data, we chose to fill the missing values with the placeholder "Unknown".

The date_added column had 10 missing values, while release_year had none. Therefore, we filled the missing values in date_added using the corresponding values from release_year, defaulting to January 1st of the release year.

Next, we examined the rating column and identified its unique values. As 'TV-MA' was the most frequent rating (mode), we filled its missing values using this value.

The duration column contained a wide range of unique values. Because it is not practical to impute missing values in this case, we chose to drop the rows with null values in duration.

We then checked for duplicate entries in the dataset. As no duplicates were found, no further action was needed.

Finally, we reviewed the data types of each column. The date_added column was converted to a proper datetime format to facilitate better time-based analysis.

