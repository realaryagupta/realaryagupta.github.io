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
-  Syntax will be np.ones((a,b)) Where a And B Are Dimension of Array

#### Method 5 - Using numpy.empty():
- Syntax will be empty_array = np.empty((a, b)) Where a And B Are Dimensions
- This Will Creates an Uninitialized Array of Specified Shape and Data Type.

#### method 6 - Using Numpy.Eye() and Numpy.Identity():
- syntax Will Be Np.Eye(a)  # Axa Identity Matrix

_________________________________

### Operations on Array




__________________________________
### Some of the Elementary Functions in Numpy

1. Max Element
- You can find the max element in array using np.max(name_of_Array)
- if you want to find the max element in row then pass an additional argument as axis=0)
- The default is coloumn which means axis=1

2. Min Element
- You can find the min element in array using np.min(name_of_Array)
- if you want to find the min element in row then pass an additional argument as axis=0)
- The default is coloumn which means axis=1

3. Sum of array
-  We can find the sum of the array using this function by simply callins np.sum(array)
-  

4. Product of array
- We can find the Product of the array using this function by simply callins np.prod(array)

5. Dot Product of 2 Arrays.
- You can perform dot product of two arrays using np.dot(arr_1,arr_2)
- 

6. Rouding a Number
- You can round a number using np.round()
- You can pass either an indivisual number or a list whose each value will be rounded of to the nearest number

7. Flooring a Number
- The numpy.floor() function returns the largest integer less than or equal to each element.
- Syntax will be np.floor(3.14159) will return 3.
- It can be applied on a array also.
8. Cieling a Number
- This Function returns the next integer number that is more than or equal to input number or list.
- For Tuple you have to convert the tuple to either list or array and then apply these functions.






________________________________________________
### Advanced Numpy Functions
1. astype() -
    - array_name.astype() - here we can pass data type by the following syntax np.int32 to convert data type.
    - This is mostly used when integers like age are mentioned in float to reduce the size of data.
2. Sort()
    - Syntax is np.sort(array)
    - This Function sorts the array into accending order by default but can be changed to descending order by np.sort(array)[::-1]
3. Append()
    - Syntax is np.append(array,new_number or list)
    - This Function appends a number or list to numpy array.
4. Concatenate()
    - Syntax is np.concatenate((arr1, arr2), axis=0 or 1)
    - This Function concatenates two arrays about a axis.
5. Unique()
    - Syntax is np.unique(array)
    - This Function is used to find the number of unique values in the array
6. Expand Dimnesions

7.Where()
    - Syntax is np.where(condition or lambda function)
    - Other way to use this np.where(condition, if condition is true then keep it in arr , else replace with something like 0 or 1) 
    - Used when we want to find elements that satisfy our condition
    - 
8. argmax()
    - syntax is np.argmax(array)
    - This Function returns the indices of the maximum values along a specified axis in an array.
    - 
9. Cumsum()
    - Syntax is np.cumsum(array)
    - This Function Returns the cumulative sum of array elements along a specified axis.
10. Histogram()
    - Syntax is np.histogram(array, len_of_bin = [list])
    - This Function returns a Histogram  
11. Correlation Coefficient
    - Syntax is np.corrcoef(array_1 , array_2)
    - This Function returns the Correaltion Coefficient of Both the Arrays
12. Isin()
    - Syntax will be np.isin(array,[Multiple items inside list])
    - 
13. Flip()
    - Syntax will be np.flip(array)
    - This Function returns the reverse of order of elements about an axis.
14. Delete()
    - Syntax will be np.delete(array, obj, axis=None)
    - This Function is used to delete elements from an array along a specified axis.
15. Put()
    - Syntax will be np.put(array, indices, values, mode='raise')
    - This Function Used to Replace Specific Elements in An Array with Given Values.
16. Clip()
    - Syntax will be np.clip(array, array_min, array_max, out=None)
    - This Function is used to limit the values in an array to be within a specified range




    
