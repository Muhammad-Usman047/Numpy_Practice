# NumPy Practice Notebook

This repository contains my practice work using NumPy in Python through a Jupyter Notebook.
The goal of this notebook is to understand how NumPy works and why it is more efficient than Python lists for numerical and scientific computing.

## Why NumPy is Superior to Python Lists

The notebook demonstrates, with code examples, why NumPy arrays are faster and more efficient than standard Python lists when working with large numerical datasets. It highlights performance, memory efficiency, and vectorized operations.

## Topics Covered

### Array Creation

* Creating 2D arrays
* `zeros()` – creating arrays filled with zeros
* `ones()` – creating arrays filled with ones
* `identity()` – creating identity matrices
* Creating sequences using `start`, `stop`, and `step`
* `full()` – creating arrays filled with a specific value

### Array Attributes

Understanding important NumPy array properties:

* `size`
* `dtype`
* `ndim`
* `shape`

### Data Type Conversion

* `astype()` for converting data types within arrays

### Mathematical Operations

* Arithmetic operators on arrays

### Aggregation (Summary) Functions

Performing statistical operations on arrays:

* `sum()`
* `mean()`
* `median()`
* `max()`
* `min()`
* `var()` – variance
* `std()` – standard deviation

### Indexing and Slicing

* Indexing (accessing a single element)
* Slicing (accessing multiple elements)

### Fancy Indexing

Selecting multiple elements at once using index arrays.

### Boolean Filtering

Extracting data based on conditions using Boolean masking.

### Reshaping Arrays

* Changing the dimensions of an array without changing the data
* Example: converting 1D arrays to 2D or 3D arrays
* Returns a view of the original data

### Flattening Arrays

Converting multi-dimensional arrays into a 1D array.

### Adding Elements

* `insert()` – inserting elements into arrays
* Inserting elements into 2D arrays
* `append()` – adding elements at the end

### Combining Arrays

* Concatenation of arrays
* Stacking arrays:

  * `vstack()` – vertical stacking
  * `hstack()` – horizontal stacking

### Splitting Arrays

Dividing arrays into multiple sub-arrays.

### Broadcasting

Using NumPy broadcasting to perform operations efficiently without loops.

Examples include:

* Broadcasting with a single value
* Broadcasting with 2D arrays

### Vectorization

Using vectorized operations for efficient matrix computations without explicit loops.

### Handling Missing and Infinite Values

Techniques for detecting and handling problematic values in datasets:

* `np.isnan()` – detects missing values
* `np.nan_to_num()` – replaces NaN values with numbers
* `np.isinf()` – detects infinite values
* Replacing NaN and infinite values within arrays

## Tools Used

* Python
* NumPy
* Jupyter Notebook (Anaconda)

## Purpose

This notebook serves as a learning and practice resource for understanding NumPy fundamentals and preparing for data analysis and machine learning workflows.
