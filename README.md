# NP_arrays
Problem 5 - Numpy Arrays
You’re given 20 integer measurements from a sensor (math/data exercise). Write Python code using NumPy arrays to compute results and transform the data.



[12, 15, 7, 9, 18, 21, 14, 16, 11, 13, 25, 19, 8, 10, 17, 20, 22, 24, 6, 23]

A) Create & Inspect
Create a NumPy array a from the dataset. Print:
shape, dtype, size, and the first/last 5 elements.
Convert a to float64 and store in a_float. Verify its dtype.
B) Indexing & Slicing
Get elements at indices 2, 5, 9, 14 into a new 1-D array (integer array indexing).
Slice every 3rd element starting at index 1 (i.e., a[1::3]).
Reverse the array (using slicing).
C) Basic Computations
Compute: min, max, mean, median, standard deviation (use NumPy functions only).
Standardize the array to z-scores: (a - mean) / std (vectorized).
D) Boolean Masks & Filtering
Build a mask for values ≥ 15. Use it to:
Count how many values meet the criterion.
Extract those values as a new array.
Replace all values < 10 with 10 (in a copy; do not mutate the original).


E) Reshaping & Axis Operations
Reshape a into a 4×5 matrix A (row-major). Print:
A
Row sums (A.sum(axis=1)) and column means (A.mean(axis=0)).
Extract the 2nd row and the last column (as column vector shape (4, 1)).
F) Broadcasting & Transformations
Using broadcasting, compute B = 1.1 * A + 5 (scale then shift).
Report B.shape and B[0, 0].
Add the column vector of column means of A to every row of A (broadcasting check).
