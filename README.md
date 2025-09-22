# Numpy-basics
NumPy and Matplotlib Practice

This repository contains Python code snippets demonstrating the use of NumPy for numerical computing and Matplotlib for visualization. It covers array creation, manipulation, mathematical operations, random number generation, filtering, reshaping, and plotting.

📌 Features Covered
🔹 Array Creation

Convert Python lists into NumPy arrays

Create multi-dimensional arrays

Initialize arrays with:

np.zeros() → Array of zeros

np.ones() → Array of ones

np.eye() → Identity matrix

np.arange() → Sequential numbers

np.linspace() → Evenly spaced numbers

🔹 Array Attributes

arr.size → Number of elements

arr.shape → Shape of array

arr.dtype → Data type of elements

arr.ndim → Number of dimensions

🔹 Random Functions

np.random.rand() → Random values between 0 and 1

np.random.randn() → Random values from normal distribution

np.random.randint() → Random integers in a range

Setting seed with np.random.seed() for reproducibility

🔹 Array Operations

Reshaping arrays → reshape()

Flattening arrays → flatten()

Copy vs Shallow Copy → copy() vs =

Transpose → arr.T or np.transpose()

Concatenation → np.concatenate(), np.hstack(), np.vstack()

🔹 Mathematical Operations

Element-wise addition, multiplication, floor division

Matrix multiplication → dot()

Statistical functions:

max(), min(), sum()

mean(), median(), percentile()

var(), std()

🔹 Filtering & Conditions

Boolean filtering → arr[arr > 5]

Conditional replacement → np.where()

Example: Replace even numbers with 100

🔹 Sorting

np.sort() with different axes and algorithms (quicksort, etc.)

🔹 Visualization with Matplotlib

Histogram of normally distributed random values using:
