Numpy:
  1. `Creating Numpy Arrays`
     - np.array
  2. `NumPy array from existing data`
     - np.asarray
  3. `Array Attributes`
      - arange
      - reshape
      - identity
      - random, randint, rand
      - uniform
      - linspace
      - zeros
  4. `Array Operations`
       - prod
       - dot
  5. `Indexing and Slicing`
  6. `Iterating`
  7. `Stacking`
  8. `Splitting`
  9. `transpose`
- delete
- copy, deepcopy
- repeat
- tile
- unique
- sort, argsort
- nanargmax, nanargmin
- where, argwhere, extract

**[Link 1](https://numpy.org/doc/stable/reference/generated/numpy.array.html_)** <br/>
**[Link 2](https://numpy.org/doc/stable/reference/_)**
NumPy (Numerical Python) is a powerful library in Python that provides support for working with arrays and matrices of numerical data, along with a wide range of mathematical functions to operate on these arrays. It's widely used in scientific computing, data analysis, and machine learning due to its efficiency and convenience.

At the core of NumPy is the `ndarray` (n-dimensional array) class, which is a multi-dimensional array object that allows you to store and manipulate large amounts of homogeneous numerical data efficiently.

Here are some key concepts to understand about NumPy arrays:
 - **Homogeneous Data**: Unlike Python's built-in lists, NumPy arrays are designed to store elements of the same data type, which leads to more efficient memory usage and faster mathematical operations.
 - **Shape and Dimensions**: A NumPy array can have one or more dimensions, often referred to as axes. The shape of an array refers to the length of each axis. For example, a 1-dimensional array might have a shape of `(5,)`, a 2-dimensional array might have a shape of `(3, 4)` (3 rows and 4 columns), and a 3-dimensional array might have a shape of `(2, 3, 4)`.
 - **Creating Arrays**: You can create NumPy arrays using various methods, such as `numpy.array()`, `numpy.zeros()`, `numpy.ones()`, `numpy.arange()`, `numpy.linspace()`, and more.
-  **Indexing and Slicing**: NumPy arrays can be indexed and sliced to access specific elements or subarrays. Indexing starts from 0, and negative indices count from the end.
 - **Array Manipulation**: NumPy offers functions to manipulate arrays, such as reshaping, transposing, stacking, and splitting arrays.
 -  **Array Concatenation**: You can combine multiple arrays together along specified axes using functions like `numpy.concatenate()` and `numpy.stack()`.