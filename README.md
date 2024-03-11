# scatter-plot
import numpy as np
import matplotlib.pyplot as plt
x=np.random.randn(50)
y1=np.random.randn(50)
y2=np.random.randn(50)
plt.scatter(x,y1,color='gold')
plt.scatter(x,y2,color='black')
plt.rcParams.update({'figure.figsize':(10,8),'figure.dpi':100})
plt.title('color change')
plt.xlabel('x-value')
plt.ylabel('y-value')
plt.show()
