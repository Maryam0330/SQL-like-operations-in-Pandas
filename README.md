# SQL-like-operations-in-Pandas
In this repository, I have performed some Pandas operations which are equivalent to SQL. 

Here are some Pandas operations that I have performed which are equivalent to SQL Queries:

- **Rename** : Renamed column names for a better understanding using the `rename()` function in Pandas.

- **Dimensions** : Retrieved dimensions using the `shape` attribute to get the dimensions of the DataFrame in Pandas, which is represented as a tuple containing two values: the number of rows and the number of columns. 

- **Datatypes** : Retrieved datatypes using the `dtypes` attribute to obtain the data types of each column in a DataFrame in Pandas. 

- **Sort** : Sorted values of specific column using the `sort_values()` method in Pandas. 

- **SELECT statement** : Retrieved all the rows and columns of the DataFrame by simply using the name of the DataFrame.  

- **SELECT...WHERE** : Retrieved a single column by specifying single condition.
By using the `&` element-wise logical AND operation retrieved two columns by specifying two conditions. Also retrieved all columns in a DataFrame by specifying multiple conditions, Retrieved subset of columns by specifying multiple conditions. 

- **LIMIT** : Used limit statement to fetch a limited number of rows using the `head()` method by specifying limit inside the parenthesis.

- **DISTINCT** : Retrieved unique rows of a specific column using the `unique()` method in Pandas.

- **Aggregation** : Used `agg()` method to get the values of aggregation functions such as 'sum', 'mean', 'min', 'max' in Pandas DataFrame.
 
- **ORDER BY clause** :  i) ASCENDING ORDER (Default) - Sorted values of specific columns using the `sort_values()`method. ii) DESCENDING ODRER - Sorted values using `sort_values()` method and by using attribute `ascending = False` inside the parenthesis of `sort_values` method in order to sort the values in descending order. 

- **GROUP BY clause** : i) GROUP BY clause with aggregation: Used `groupby()` method to calculate the sum and count of specific columns in the DataFrame by grouping the values in the column. ii) GROUP BY (Count and Descending order) : Used `groupby()` method to calculate the count of specific columns in the DataFrame by grouping the values in the column in descending order by using the parameter `ascending = False` inside the `sort_values()` method.

- **HAVING clause** - Used `group_by()` , `filter()`, `size()` to filter aggregated data, specified condition that involved COUNT(*) function and filtered groups based on those conditions.

- **IN and NOT IN** : Used `isin()` method to check if the specific values are present in the column. Whereas to check if the values are not present in column, used ~ and `isin()` method.

- **Top N observations with and without Offset** : Offset is the number of rows to skip from the beginning of the result set. Skipping the first 10 rows and retrieved the next 10 rows using the `nlargest()` and `tail()` method in Pandas. 'nlargest()' returns the top N largest values based on the specified column.

- **UNION and UNION ALL** - Used `concat()` method in Pandas to eliminate and retain duplicates in two DataFrames.

- **JOIN operation** : Used the `merge()` method in Pandas to 'LEFT JOIN', 'RIGHT JOIN' and 'INNER JOIN' on two DataFrames. Used the `how` parameter in merge() function to specify the type of join. 

- **INSERT** : Inserted a new record in the table using the `append()` method.

- **UPDATE** : Updated columns in a DataFrame using the `.loc` attribute.

- **DELETE** : Deleted/ Dropped existing records and columns in a DataFrame using the `drop()` method.
