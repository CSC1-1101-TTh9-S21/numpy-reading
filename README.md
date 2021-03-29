# Getting started with NumPy

### Step 1
Install the NumPy, SciPy, pandas, and matplotlib libraries by following the same instructions you used to install PySimpleGUI for problem set 7. Namely: launch Terminal (on Mac), or Command (on Windows) and type the following, replacing `pip3` with `pip` on Windows (I think):

```
pip3 install numpy 
```

and then

```
pip3 install scipy
```

and then

```
pip3 install matplotlib
```

and then

```
pip3 install pandas
```

### Step 2
Confirm that you installed these libraries correctly by going to the IDLE shell and typing

```
import numpy as np
import scipy
import matplotlib.pyplot as plt
import pandas as pd
```

### Step 3
Read [this brief page about importing modules](https://www.digitalocean.com/community/tutorials/how-to-import-modules-in-python-3).

### Step 4
Read [this very brief introduction to NumPy](https://www.w3schools.com/python/numpy/numpy_intro.asp)

Read these pages in order, and try out the code **in IDLE**:

* [Creating NumPy Arrays](https://www.w3schools.com/python/numpy/numpy_creating_arrays.asp)

* [NumPy Array Indexing](https://www.w3schools.com/python/numpy/numpy_array_indexing.asp)

* [NumPy Array Slicing](https://www.w3schools.com/python/numpy/numpy_array_slicing.asp)

* [Getting subarrays matching some conditional](https://thispointer.com/python-numpy-select-elements-or-indices-by-conditions-from-numpy-array/)


### Step 5
Read these pages about the aggregate functions in numpy:

* [Option 1](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/02.04-Computation-on-arrays-aggregates.ipynb)
* [Option 3](https://www.pythonprogramming.in/numpy-aggregate-and-statistical-functions.html)
* [Option 2](https://www.tutorialgateway.org/python-numpy-aggregate-functions/)


## Step 6
Read these helpful pages:

* [`unique()`](https://www.tutorialspoint.com/numpy/numpy_unique.htm)
* [`where()`](https://thispointer.com/find-the-index-of-a-value-in-numpy-array/)

### Step 7

Copy and paste this code, **one line at a time**, into the IDLE shell for a treat:

```
from scipy import misc
import matplotlib.pyplot as plt
face = misc.face()
plt.imshow(face)
plt.show()
```



