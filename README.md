## Numpy Essentials

### What is the Difference between Numpy Array and Python List
Numpy arrays are similar to python list in essence but they can do much more than lists.\
Here Are Some Benefits of Using Numpy Array Over Python List.
1. Numpy Arrays Can Perfrom Much More Mathematical Computation than Lists.
2. Numpy Function and routines are written in C++ and C so it has the speed of C++ and Syntax of Python which makes them easy to use and highly efficient in operation.
3. Numpy Arrays Have Fixed Size (when creating) and uses less memory Unlike Lists Which Are Dynamic in Size and reqire large memory.
4. Elements in numpy array must have same dtype and if you put other dtype then it will be casted to upper dtype(more on this later in this series).
5. Data is stored in continous memory location in numpy array
6. Numpy arrays also support element-wise operations on arrays.

### Attribute of an Array
1. Dimension of Array - The Dimension of An Array Can Be Easily Determined by Using array_name.ndim
2. Shape of Array - The Shape of an array can be determined by using array_name.shape
3. Size of Array - The Size of an array means the Number of elements in an array. it can be found using array_name.size
4. Data Type of an Array - The data type means that what type of data is contained in the array is it int or float32 or float64.
5. Item Size of an Array - [[Write Later ]]

___________________________


### How to create an array 
There will be sometimes when you need to create an array although you will most of the times get already created data.\
You can create array by some methods mentioned below

#### Method 1 - Using np.array()
- Using this function you can pass a Python List or Tuple inside it to convert it array.
- You can also pass dtype to specify the type of dtype you want

#### Method 2 - Using np.arange()
- You can use this to generate numbers between a specific range. it works similar to python range funtion
- Syntax will be np.arrange(start_index,last_index,steps(optional))
- It is important to note that last_index will be exclusive and would not be included.
- 

#### Method 3 - Using numpy.linspace():
- Syntax will be np.linspace(start,stop,number of points)
- 

#### Method 4 - Using numpy.zeros() and numpy.ones():
- Syntax will be np.zeros((a,b)) where a And B Are Dimension of Array
- Syntax will be np.ones((a,b)) Where a And B Are Dimension of Array

#### Method 5 - Using numpy.empty():
- Syntax will be empty_array = np.empty((a, b)) Where a And B Are Dimensions
- This Will Creates an Uninitialized Array of Specified Shape and Data Type.

#### method 6 - Using Numpy.Eye() and Numpy.Identity():
- syntax Will Be Np.Eye(a)  # Axa Identity Matrix

_________________________________

### Operations on Array




__________________________________
### Elementary Functions in Numpy

**1. Max Element**
- Syntax: `np.max(name_of_array)` or `np.max(name_of_array, axis=0)`
- Description: Finds the maximum element in an array, optionally along a specified axis.

**2. Min Element**
- Syntax: `np.min(name_of_array)` or `np.min(name_of_array, axis=0)`
- Description: Finds the minimum element in an array, optionally along a specified axis.

**3. Sum of Array**
- Syntax: `np.sum(array)`
- Description: Finds the sum of the elements in an array.

**4. Product of Array**
- Syntax: `np.prod(array)`
- Description: Finds the product of the elements in an array.

**5. Dot Product of 2 Arrays**
- Syntax: `np.dot(arr_1, arr_2)`
- Description: Computes the dot product of two arrays.

**6. Rounding a Number**
- Syntax: `np.round(number)` or `np.round(array)`
- Description: Rounds a number or each element in an array to the nearest integer.

**7. Flooring a Number**
- Syntax: `np.floor(number)` or `np.floor(array)`
- Description: Returns the largest integer less than or equal to each element in a number or array.

**8. Ceiling a Number**
- Syntax: `np.ceil(number)` or `np.ceil(array)`
- Description: Returns the smallest integer greater than or equal to each element in a number or array.






________________________________________________
### Advanced Numpy Functions
### Functions Overview

**1. Astype()**
- Syntax: `array_name.astype(np.dtype)`
- Description: Converts data type of array elements, often used for optimizing memory usage.

**2. Sort()**
- Syntax: `np.sort(array)`
- Description: Sorts the array in ascending order by default; for descending order, use `np.sort(array)[::-1]`.

**3. Append()**
- Syntax: `np.append(array, new_number_or_list)`
- Description: Appends a number or list to a numpy array.

**4. Concatenate()**
- Syntax: `np.concatenate((arr1, arr2), axis=0 or 1)`
- Description: Concatenates two arrays along a specified axis.

**5. Unique()**
- Syntax: `np.unique(array)`
- Description: Finds the number of unique values in the array.

**6. Expand Dimensions**
- (Missing details on syntax and description)

**7. Where()**
- Syntax: `np.where(condition)`
- Alternatively: `np.where(condition, x, y)`
- Description: Finds elements satisfying a condition or replaces values based on a condition.

**8. Argmax()**
- Syntax: `np.argmax(array)`
- Description: Returns indices of maximum values along a specified axis.

**9. Cumsum()**
- Syntax: `np.cumsum(array)`
- Description: Returns cumulative sum of array elements along a specified axis.

**10. Histogram()**
- Syntax: `np.histogram(array, bins=[list])`
- Description: Returns a histogram.

**11. Correlation Coefficient**
- Syntax: `np.corrcoef(array_1, array_2)`
- Description: Returns the correlation coefficient of both arrays.

**12. Isin()**
- Syntax: `np.isin(array, [items])`
- Description: Checks whether elements in an array are contained in a specified list.

**13. Flip()**
- Syntax: `np.flip(array)`
- Description: Returns the reverse order of elements about an axis.

**14. Delete()**
- Syntax: `np.delete(array, obj, axis=None)`
- Description: Deletes elements from an array along a specified axis.

**15. Put()**
- Syntax: `np.put(array, indices, values, mode='raise')`
- Description: Replaces specific elements in an array with given values.

**16. Clip()**
- Syntax: `np.clip(array, array_min, array_max, out=None)`
- Description: Limits the values in an array to be within a specified range.




    
