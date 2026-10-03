# Data Analysis Using NumPy and Pandas

## Overview

This project demonstrates basic data analysis and manipulation using **Python, NumPy, and Pandas**.

The program works with temperature data, student marks, and transaction data to practice creating arrays and Pandas objects, inspecting data, performing calculations, filtering information, and modifying datasets.

## Tools & Libraries

* **Python**
* **NumPy** – for numerical and array operations
* **Pandas** – for Series and DataFrame operations
* **Jupyter Notebook** – for writing and executing the Python code

## What I Worked On

### 1. NumPy Array Operations

Created and analyzed one-dimensional and two-dimensional NumPy arrays using weekly temperature data.

The following operations were performed:

* Created NumPy arrays using `np.array()`
* Checked array `shape`
* Checked data type using `dtype`
* Counted elements using `size`
* Converted Celsius temperatures to Fahrenheit using arithmetic operations
* Calculated maximum, minimum, and mean temperatures using:

  * `max()`
  * `min()`
  * `mean()`
* Used array indexing and slicing to extract:

  * First three days
  * Weekend temperatures
  * Middle three days
* Created a 2D array containing temperature data for two weeks
* Extracted individual rows and weekend temperatures from the 2D array

### 2. Pandas Series

Created a Pandas Series containing student marks with custom rank labels.

The following concepts were practiced:

* Created a Series using `pd.Series()`
* Used custom indexes such as `Rank1`, `Rank2`, etc.
* Accessed values by integer position using `.iloc`
* Accessed values using index labels with `.loc`
* Selected multiple labels using `.loc`
* Used boolean masking to filter marks greater than 90
* Modified an existing value
* Removed an entry using `drop()`
* Calculated CGPA by performing arithmetic operations on the Series

### 3. Pandas DataFrame

Created a transaction DataFrame containing transaction IDs, product categories, regions, and transaction amounts.

The DataFrame section included:

* Created a DataFrame using `pd.DataFrame()`
* Inspected the data using:

  * `head()`
  * `tail()`
  * `shape`
  * `columns`
  * `dtypes`
  * `info()`
* Selected specific columns
* Used `.iloc` for row and column selection
* Filtered rows using multiple conditions
* Used `value_counts()` to analyze product categories
* Used `unique()` to identify different regions
* Used `groupby()` and `mean()` to calculate average transaction amounts by region
* Modified a transaction amount using `.loc`
* Created a new `Discount` column using arithmetic operations
* Removed a transaction using boolean filtering
* Removed a column using `drop()`

## Key Python Concepts Used

```text
NumPy
├── np.array()
├── shape
├── dtype
├── size
├── max()
├── min()
├── mean()
├── Indexing
└── Slicing

Pandas Series
├── pd.Series()
├── .loc[]
├── .iloc[]
├── Boolean filtering
└── drop()

Pandas DataFrame
├── pd.DataFrame()
├── head()
├── tail()
├── shape
├── columns
├── dtypes
├── info()
├── .iloc[]
├── .loc[]
├── value_counts()
├── unique()
├── groupby()
├── mean()
└── drop()
```

## Purpose

The purpose of this project is to build practical familiarity with **NumPy arrays, Pandas Series, and Pandas DataFrames** and to understand how Python can be used to inspect, transform, filter, and analyze structured data.

## Files

* `Python DA Assignment 1 - Data Analysis using NumPy and Pandas.ipynb` – Jupyter Notebook containing the analysis and code.
