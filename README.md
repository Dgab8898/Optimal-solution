# **Task Description**

Differential calculus can be used to analyse and applied to to complex problems in our society, its continue to make contributions to every field. 
In this task we will examine optimisation problems, where a quantity is to be maximised or minimised. These problems arise both outside and within mathematics, e.g in the construction of water line through different region.

## **Load Packages**

```
import numpy as np
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D
from scipy import optimize
```

## **Data Process**
- We used Nedler-Mead simplex algorithm method to minimize a non-linear function contianing two varaibles 
-We Define the objective function that wll minimw3**
-Next we create a grid of values that we can plot our objective function
- then we evaluate the function on this grid of points:
-Next we create  a new figure with 3d axes object and set the a title
- then we plot the objective function as a surface on the axes we just created:
- We chooose an initial point that our minimix=zation routine will start its iteration at and plot this on the surface
- We used the minimize routine from the optimize package to find minimum value.
- Finally we plot the minimum value found by the minimize routine on the top of the objective function surface.

## **Issues**
None



## **Contributing**
For major changes, feel free to discuss, and contribute, and make appropriate test.

## **Licence**
```
Copyright (C) 2021 David Gabriel
```

## **Credit**
I am sitting on the gaint shoulders of authors and programmers

## **Further reading & References**
- James Stewart - Calculus, Early Transcendantals, International Metric Edition-CENGAGE learning 2016\
- Robert A.Adams Christopher Essex - Calculus A Complete Course\
- Sam Morley - Receipe for solving computational Problems(2020)




