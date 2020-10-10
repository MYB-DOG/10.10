import matplotlib.pyplot as plt
import math
import numpy as np

def ex_func(x):
  y=math.exp(x)
  return y

X=np.linspace(-4, 4, 40)
Y=[ex_func(x) for x in X]

plt.plot(X,Y)
plt.show()
