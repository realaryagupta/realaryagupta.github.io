## What is Pandas 
- It is a Powerful library that helps to manupilate and alter Dataframe of large amount in fast amount if time.

## Pandas Library Function vs Methods
### Pandas Functions
1. They are those functions that need pandas to execute they are defined inside the pandas Library.
2. They generally involve creating, manipulating, or inspecting data structures.
3. When to use them
  - Create a new DataFrame or Series.
  - Read from or write to a file or external source.
  - Perform operations that span multiple DataFrames (like merging).
  - Use general functions that apply across pandas objects (like converting data types).

### Pandas Methods
1. They are used for operations that modify, analyze, or retrieve data from the DataFrame.
2. They involve Dealing with a particular df or a series.
3. When to use them
  - Access or manipulate the data within a specific DataFrame or Series.
  - Perform data selection, indexing, or slicing.
  - Modify the structure or labels of a DataFrame.
  - Compute statistics or perform operations on the data within a DataFrame.

## Pandas Series

### Creating a Series
1. From a List - pd.Series(list_name)
- You can also change index of the list by pd.Series(list_name,index=xyz)
- Naming the Series - pd.Series(list_name, name = "xyz")

2. Making the List using dictionary
- Creating - pd.Series(dict)

### Attributes of a Series
1. `Series_name.size` - The number of elements in the Series.
2. `Series_name.dtype` - The data type of the Series elements.
3. `Series_name.name` - The name of the Series.
4. `Series_name.is_unique` - Boolean indicating if all elements in the Series are unique.
5. `Series_name.index` - The index (labels) of the Series.
6. `Series_name.values` - The underlying NumPy array of the Series.
7. `Series_name.data` - Actual data of the Series.
8. `Series_name.shape` - The shape of the Series (a tuple).
9. `Series_name.hasnans` - Boolean indicating if the Series contains NaN values.

### Importing a Series
1. From CSV - pd.read_csv()


### Series Methods
Sure! Here are the explanations formatted in Markdown:

1. `Series_name.head()` - Returns the first n elements of the Series.
2. `Series_name.tail()` - Returns the last n elements of the Series.
3. `Series_name.sample()` - Returns a random sample of elements from the Series.
4. `Series_name.value_counts()` - Returns a Series containing counts of unique values.
5. `Series_name.sort_values()` - Sorts the Series by its values.
6. `Series_name.index` - Provides the labels (index) of the Series.

### Series Math Methods

1. `Series_name.sum()` - Returns the sum of the Series elements.
2. `Series_name.describe()` - Generates descriptive statistics of the Series.
3. `dir(Series_name)` - Lists all methods and attributes of the Series (note: there is no `methods` attribute).
4. `Series_name.min()` - Returns the minimum value of the Series.
5. `Series_name.max()` - Returns the maximum value of the Series.


### Slicing a Series


## Pandas Dataframe










## General Functions of Pandas 
1. Pivot Table






















