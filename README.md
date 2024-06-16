# Python for Data Analysis

I'm working my way through 'Python for Data Analysis' by Wes McKinney. It's a great resource for learning data analysis with Python. This book is excellent for understanding the concepts of Data Analysis using pandas and NumPy, it also provides basic understanding of data visulization and modeling libraries in Python. I'm particularly finding the hands-on case studies in 'Python for Data Analysis' helpful for understanding how to apply these concepts to real-world problems. I'm using this book to build my skills in data analysis with Python. The book's focus on real-world datasets is exactly what I need to achieve my goals in this field. Some useful links:

- [Book PDF](https://github.com/Harshit1234G/Python-for-Data-Analysis/blob/master/0_python-for-data-analysis-data-wrangling-with-numpy--annas-archive--libgenrs-nf-3422197.pdf)
- [Wes McKinney website link for online book](https://wesmckinney.com/book/)
- [This book's github repository by Wes McKinney](https://github.com/wesm/pydata-book)

## What I learnt from this book?

- **Chapter 1 - Preliminaries:** What is Data Analysis, Why to use Python for Data Analysis, Basic description about libraries like pandas, NumPy, SciPy, scikit-learn, statsmodels and other packages. About Jupyter and ipython, IDEs and some basic stuff.
  
---

- **Chapter 2 - Python Language Basics, IPython, and Jupyter Notebooks:** About Python and IPython terminals, Jupyter Notebook and basics of Python Language.
  
---

- **Chapter 3 - Built-In Data Structures, Functions, and Files:** Built-In Data Structures (tuple, list, dict, set) and there comprehensions, functions, generators, execption handling and file handling.
  
---

- **Chapter 4 - NumPy Basics: Arrays and Vectorized Computation:**
  - From this chapter the proper Data Science part has started, I got to know that NumPy is written in C, C++ and FORTRAN. This makes NumPy extremely fast (way faster than native Python code).
  - The NumPy `ndarray` object is a fast n-dimensional array object.
  - Creating ndarray, its attributes (like shape, dtype, ndim, etc), mathematical operations on ndarray and various other NumPy functions on ndarray.
  - There are various datatypes(dtypes) in NumPy, different sized integers, floats, complex numbers, boolean, string_, etc.
  - How to change and check the dtype.
  - Basic indexing, slicing, fancy indexing, and boolean indexing.
  - Transposing arrays and swaping axes.
  - Various functions regarding random number generation like, `np.random.standard_normal()`.
  - Fast element-wise array functions called *ufuncs* (Universal Functions).
  - Using `np.where` for conditional logic.
  - Various other mathematical and statistical methods (like, `np.sum`, `np.mean`, `arr.cumsum`, etc).
  - Methods on boolean arrays, sorting, and other set logic.
  - Linear algebra and random walk using NumPy, File I/O of arrays.
  
---

- **Chapter 5 - Getting Started with pandas:**
  - pandas data structures: `Series`, `DataFrame`, `Index`.
  - `pd.Series:` It is a one-dimensional array like object containing a sequence of values of the same type and an associated array of data lables called *index*. I got to know about simple and boolean indexing, slicing, mathematical operations, and other methods regarding Series object.
  - `pd.DataFrame:` A DataFrame represents a rectangular table of data and contains an ordered, named collection of columns, each of which can be a different data type. The DataFrame has both a row and column index; it can be thought of as a dictionary of Series all sharing the same index. What I learnt about DataFrame:
    1. Creating DataFrame using dictionary and other methods of creating DataFrame.
    2. Slicing a particular value, row, columns or part of DataFrame using basic slicing syntax and by using `loc` and `iloc`.
    3. Adding columns and rows, and assigning values.
    4. Transposing, head, tail and various other DataFrame functions.
  - `pd.Index:` Index object is used as index in both Series and DataFrame.
  - Reindexing of Series and DataFrame.
  - Droping entries from an axis.
  - Indexing, slicing and filtering. Types of indexing and their pitfalls.
  - Arithmetic operations of DataFrame and Series, and operations between them.
  - Applying function and mapping values.
  - Sorting and Ranking.
  - Descriptive Statistics in DataFrame.
  - Correlation and Covariance.
  - Getting Unique values, Value counts, and Membership.

---

- **Chapter 6 - Data Loading, Storage, and File Formats:**
  - Reading data from *.txt* or *.csv* file using `pd.read_csv` and `pd.read_table`, also reading files with different delimiters.
  - In real world, data could be a lot messy, so these functions have various arguments to read every type of text file. We could determine various properties to read the file.
  - Writing data to text format using `df.to_csv()` function. It takes a DataFrame and writes it to a *.csv* file.
  - It also describes how to read files with different format like JSON, XML, HTML and Binary Data Formats.
  - How to read and write data in pickle(.pkl), HDF5(.h5) and Excel(.xlsx) files.
  - Also given an idea of `requests` module to interact with web APIs.
  - Also give and idea of `sqlite3` module to interact with Databases.

---

- **Chapter 7 - Data Cleaning and Preparation:**
> In real world, the data could be pretty messy. This chapter focused on data cleaning and preparation to transform messy data into a form which is suitable for analysis.
> Following are the techniques that I learned to clean and prepare data:
  - Handling missing data, in pandas missing value is represented by `NaN` or `<NA>`, so the book describes how to check if there are any NULL values, filtering them out, filling them with some other value.
  - Data transformation.
  - Removing duplicates.
  - Replacing values.
  - Renaming axis indexes.
  - Discretization: Getting discrete values from continous values.
  - Binning values to categories using `pd.cut` and `pd.qcut`.
  - Detecting and filtering outliers.
  - Permutation and random sampling.
  - Converting a categorical variable into dummy variable (generally used in machine learning).
  - Extension datatypes and why they are better.
  - Built-in Python string manipulation and regex.
  - pandas string functions using `DataFrame.str`.
  - Categorical datatype and why it is better to use categorical in place of sting.

---

- **Chapter 8 - Data Wrangling: Join, Combine, and Resahpe:**
  - pandas MultiIndex object (`pd.MultiIndex`) to implement hierarchical indexing.
  - stacking, unstacking and resetting index of MultiIndex.
  - Swaping level of MultiIndex and Sorting by different levels of index.
  - Different ways of joining, merging, concatenating and combining different DataFrames.
  - Reshaping of index.
  - Creating pivot tables and melting DataFrames.

---

- **Chapter 9 - Plotting and Visualization:** Data Visualization using `matplolib.pyplot`, `seaborn` and `pandas` itself. Different kind of plots, subplots, saving plots to secondary memory, etc.

---

- **Chapter 10 - Data Aggregation and Group Operations:**
  - Using split-apply-combine technique to group and aggregate data using `df.groupby`.
  - This chapter helped me to understand various ways of using groupby and aggregation functions.
  - Also given some real life examples for grouping and aggregation.
  - Pivot table and cross-tabulations.

---

- **Chapter 11 - Time Series:**
  - Python's datetime module.
  - Basics of time series.
  - Date Ranges, Frequencies, and Shifting.
  - Time zone handling, localization and conversion.
  - Periods and period arithmetic.
  - Resampling and Frequency Conversion.
  - OHLC resmapling.
  - Downsampling, upsampling and Interpolation.
  - Moving window functions.

---

- **Chapter 12 - Introduction to Modeling Libraries in Python:** Basics of modeling libraries like `patsy`, `statsmodels`, and `scikit-learn`.

---

- **Chapter 13 - Data Analysis Examples:**
> In this chapter data analysis is done on 5 real life datasets.
  1. [Bitly Data from 1.usa.gov](https://github.com/Harshit1234G/Python-for-Data-Analysis/blob/master/ch_13_project1.ipynb)
  2. [MovieLens 1M Dataset](https://github.com/Harshit1234G/Python-for-Data-Analysis/blob/master/ch_13_project2.ipynb)
  3. [US Baby Names 1880-2010](https://github.com/Harshit1234G/Python-for-Data-Analysis/blob/master/ch_13_project3.ipynb)
  4. [USDA Food Database](https://github.com/Harshit1234G/Python-for-Data-Analysis/blob/master/ch_13_project4.ipynb)
  5. [2012 Federal Election Commission Database](https://github.com/Harshit1234G/Python-for-Data-Analysis/blob/master/ch_13_project5.ipynb)

---

- **Appendix A - Advanced Numpy:**
  - ndarray object internals.
  - C Versus FORTRAN order.
  - Some other advanced features of NumPy.
  - Numba
  - Performance tips.

---
