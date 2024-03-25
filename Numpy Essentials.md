
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









1. astype() -
- array_name.astype() - here we can pass data type by the following syntax np.int32 to convert data type.
- This is mostly used when integers like age are mentioned in float to reduce the size of data.
-  





