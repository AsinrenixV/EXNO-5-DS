# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
# NAME : ASIN RENIX V
# REG NO : 212224040036
# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
# Line Plot:
```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```

<img width="319" height="438" alt="image" src="https://github.com/user-attachments/assets/49b3add9-2851-450d-b2d7-f39ae4237132" />

# Scatter Plot:
```
x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

<img width="344" height="440" alt="image" src="https://github.com/user-attachments/assets/8b031ea0-b6af-4097-8e61-b9f2c9b5bb8a" />

# Pie Chart:
```
act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

<img width="333" height="413" alt="image" src="https://github.com/user-attachments/assets/807931a5-53d9-4517-a508-632cdbc56a22" />

# Area Chart:
```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

<img width="321" height="215" alt="image" src="https://github.com/user-attachments/assets/df5a1cd6-73e6-4499-b15a-9ec81f447ff8" />

# Bar Chart:
```
height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```

<img width="343" height="237" alt="image" src="https://github.com/user-attachments/assets/93f0d0ff-ea73-4e5a-b12f-9206c800716c" />

# Histogram:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

<img width="326" height="215" alt="image" src="https://github.com/user-attachments/assets/d31c6da3-d282-4351-bc73-13e7163992c4" />

# Box Plot:
```
np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```

<img width="311" height="183" alt="image" src="https://github.com/user-attachments/assets/59e199b5-e4c7-4b4a-9a1e-f2b7ceaf479b" />

```
fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```

<img width="333" height="243" alt="image" src="https://github.com/user-attachments/assets/b009e052-ac20-4708-8e8f-773a595ad711" />



# Result:

Thus, all the data visualization techniques of matplotlib has been implemented.
