#!/usr/bin/env python
# coding: utf-8

# In[47]:


import pandas as pd
import xlrd
import matplotlib.pyplot as plt
import matplotlib.ticker as tk
from mpl_toolkits.mplot3d.axes3d import Axes3D
import matplotlib.cm as cm
import seaborn as sns
plt.style.use('seaborn')
get_ipython().run_line_magic('matplotlib', 'notebook')
import pylab as pl
import numpy as np
from scipy.interpolate import lagrange
from scipy.special import legendre
import math
sns.set()
pd.__version__


# In[14]:


m = np.array([[958603863.3765 , 911766544.1164],[911766544.1164 , 963665233.3609]])
m


# In[15]:


valores2, vectores2 = np.linalg.eig(m)


# In[16]:


df1 = pd.read_excel("./dats1.xlsx")


# In[17]:


df1


# In[18]:


valores2


# In[19]:


vectores2


# In[20]:


float(4.93644922e+07)


# In[21]:


float(1.87290460e+09)


# In[22]:


df2 = pd.read_excel("./dats2.xlsx")
df2


# In[23]:


m2 = np.array([[958603863.3765 , 911766544.1164 , -7134226.8564],[911766544.1164 , 963665233.3609 , -1927462.5926],[-7134226.8564 , -1927462.5926 , 101844216.7918]])
m2


# In[24]:


valores3, vectores3 = np.linalg.eig(m2)


# In[25]:


valores3


# In[26]:


vectores3


# In[30]:


float(1.87292775e+09)


# In[32]:


float(4.91061110e+07)


# In[33]:


float(1.02079453e+08)


# In[42]:


df3=pd.read_excel("./dats2graf.xlsx")
df3
x=df3['x']
y=df3['y']
z=df3['z']


# In[49]:


fig, ax = plt.subplots(figsize=(10,10))
ax=fig.add_subplot(111,projection="3d")
ax.scatter3D(x,y,z,)
plt.show()


# In[50]:


x1=df2['x']
y1=df2['y']
z1=df2['z']


# In[51]:


fig, ax = plt.subplots(figsize=(10,10))
ax=fig.add_subplot(111,projection="3d")
ax.scatter3D(x1,y1,z1,)
plt.show()

