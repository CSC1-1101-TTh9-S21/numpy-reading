# NumPy and SciPy

I was not able to find a NumPy or SciPy reading that I liked, so I am going to cobble together my own.

### Step 1
Install the NumPy and SciPy libraries by following the same instructions you used to install PySimpleGUI for problem set 7. Namely: launch Terminal (on Mac), or Command (on Windows) and type the following, replacing `pip3` with `pip` on Windows (I think):

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

### Step 2
Confirm that you installed these libraries correctly by going to the IDLE shell and typing

```
import numpy as np
import scipy
import matplotlib.pyplot as plt
```

### Step 3
Read [this brief page about importing modules](https://www.digitalocean.com/community/tutorials/how-to-import-modules-in-python-3).

### Step 4
Read [this very brief introduction to NumPy](https://www.w3schools.com/python/numpy/numpy_intro.asp)

And look at the section [on this page](https://www.w3schools.com/python/numpy/numpy_getting_started.asp) called NumPy as `np`.

### Step 5
Read these pages in order, and try out the code **in IDLE**:

* [Creating NumPy Arrays](https://www.w3schools.com/python/numpy/numpy_creating_arrays.asp)

* [NumPy Array Indexing](https://www.w3schools.com/python/numpy/numpy_array_indexing.asp)

* [NumPy Array Slicing](https://www.w3schools.com/python/numpy/numpy_array_slicing.asp)


### Step 6

Copy and paste this code, **one line at a time**, into the IDLE shell for a treat:

```
from scipy import misc
import matplotlib.pyplot as plt
face = misc.face()
plt.imshow(face)
plt.show()
```



