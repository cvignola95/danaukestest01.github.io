```python
%matplotlib inline
```

    Matplotlib is building the font cache; this may take a moment.



```python
import matplotlib.pyplot as plt
import numpy
```

## Introduction

Here is some text


```python
x = numpy.r_[0:1:.01]
y = numpy.sin(x)
plt.plot(x,y)
```




    [<matplotlib.lines.Line2D at 0x7f99d13e3fd0>]




    
![png](output_3_1.png)
    

