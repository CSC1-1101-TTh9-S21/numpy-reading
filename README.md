# Getting started with numpy and other modules

### Step 1
You are now officially great at writing and running programs in IDLE. Starting this week, we are going to start coding with Colab notebooks. I will demonstrate this in class on Tuesday, but in the meantime, you should [get started by following this link to your first Colab notebook](https://colab.research.google.com/drive/1Hy3pEZG0WQK6RCmWryiO1GfT6h4cTWtP?usp=sharing) and following the instructions provided there. Once you've followed those instructions, you can re

### Step 2
Read [this very brief introduction to NumPy](https://www.w3schools.com/python/numpy/numpy_intro.asp)

Read these pages in order, and try out the code in your Colab notebook.

* [Creating NumPy Arrays](https://www.w3schools.com/python/numpy/numpy_creating_arrays.asp)

* [NumPy Array Indexing](https://www.w3schools.com/python/numpy/numpy_array_indexing.asp)

* [NumPy Array Slicing](https://www.w3schools.com/python/numpy/numpy_array_slicing.asp)

* [Getting subarrays matching some conditional](https://thispointer.com/python-numpy-select-elements-or-indices-by-conditions-from-numpy-array/)


### Step 3
Read these pages about the aggregate functions in numpy:

* [Option 1](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/02.04-Computation-on-arrays-aggregates.ipynb)
* [Option 3](https://www.pythonprogramming.in/numpy-aggregate-and-statistical-functions.html)
* [Option 2](https://www.tutorialgateway.org/python-numpy-aggregate-functions/)


### Step 4
Read these helpful pages:

* [`unique()`](https://www.tutorialspoint.com/numpy/numpy_unique.htm)
* [`where()`](https://thispointer.com/find-the-index-of-a-value-in-numpy-array/)

### Step 5

Copy and paste this code into a code cell in the Colab notebook you created in Step 1 for a fun treat!

```
from scipy import datasets
import matplotlib.pyplot as plt
face = datasets.face()
plt.imshow(face)
plt.show()
```



