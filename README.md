# PHSX 815: Week 9
## 3D Plot Minimization

This repository includes a script that gives the minimum of a 3D function and plots it on a mesh grid. 

This is the same code as homework 9 as I wrote that code for a 3D function already. No changes have been made.

---

### Homework 10:

### Running the Code
The construction plots are made by the `Neyman_Construction.py` python file. This file requires python3 to run, and includes the following packages listed at the top of the script:

```
  import numpy as np
  from scipy.optimize import minimize
  import matplotlib.pyplot as plt
  from mpl_toolkits.mplot3d import Axes3D
  import sys
```

To run this script from the terminal in linux, run:

> $ python3 Minimization.py

This runs the file with the default parameters which is a resolution of 100 in the mesh grid for the plot. This can be changed from the terminal.

For example, it may looks something like this in linux:

> $ python3 Minimization.py -res 50

which would plot the 3D surface with a resolution of 50 instead of 100 points in each axis.

### The Output

The first output is the coordinate of the minimum, along with the evaluated function value at that point. Then, it plots the surface with the minimum point in red:

![Figure_11](https://user-images.githubusercontent.com/76142511/228123943-4b53fd15-04c6-4e12-8705-85e577ecaffd.png)

SOURCES: Help was from the following [stack overflow page.](https://stackoverflow.com/questions/55058969/find-global-minimum-scipy-and-display-it-on-3d-graph)



