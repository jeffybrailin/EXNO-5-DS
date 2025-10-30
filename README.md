## Name: Jeffy Brailin T
## Reg.No: 212223040076

# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

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

import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```

<img width="746" height="534" alt="image" src="https://github.com/user-attachments/assets/523ddedb-fa13-4b32-8052-0a68ffd47cc2" />

```

import matplotlib.pyplot as plt
x_values=[1,2,3]
y_values=[2,4,1]
plt.plot(x_values,y_values)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()

```

<img width="765" height="580" alt="image" src="https://github.com/user-attachments/assets/db5afac3-a362-41f3-8998-8af5ff4d96b0" />

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')

x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()


```

<img width="719" height="583" alt="image" src="https://github.com/user-attachments/assets/eafc08e8-8bb1-489a-9691-b7ca2fb0f4da" />


```
import matplotlib.pyplot as plt
x_values=[1,2,3,4,5,6]
y_values=[2,4,1,5,2,6]
plt.plot(x_values,y_values,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlim(1,8)
plt.ylim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()

```
<img width="743" height="571" alt="image" src="https://github.com/user-attachments/assets/e3283f86-f9c9-4da2-83ae-e2fa74b00276" />

```

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)

```

<img width="825" height="558" alt="image" src="https://github.com/user-attachments/assets/4d58fa0a-2cde-4bf5-832c-e47471fb0481" />


```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
years=[2010,2011,2012,2013,2014,2015]
plt.plot(years,yield_apples)

```

<img width="842" height="570" alt="image" src="https://github.com/user-attachments/assets/9f90d404-8a2e-44ce-a910-8a7dafdc97ce" />


```

apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')

```
<img width="868" height="588" alt="image" src="https://github.com/user-attachments/assets/8266a06e-e492-4f3f-9641-1f177fb18033" />

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yield in Kanto")
plt.legend(['Apples','Oranges'])


```

<img width="858" height="617" alt="image" src="https://github.com/user-attachments/assets/68d00711-61d6-4f28-9831-b5701393529f" />

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
years=[2010,2011,2012,2013,2014,2015]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')

```
<img width="885" height="595" alt="image" src="https://github.com/user-attachments/assets/0616bcbc-7160-46c4-8849-16aca767a060" />

```

apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons of hectares)")

```
<img width="1342" height="702" alt="image" src="https://github.com/user-attachments/assets/71ea2f69-e27d-413e-990d-cf6788537f47" />

```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yield in Kanto")
plt.legend(['Apples','Oranges'])

```

<img width="840" height="611" alt="image" src="https://github.com/user-attachments/assets/8989d007-a9aa-4832-8bcc-d9f9bd3f0efb" />


```

import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color='blue')
plt.show()

```
<img width="747" height="529" alt="image" src="https://github.com/user-attachments/assets/bc91783a-292c-418a-a20c-3819d4acd4b1" />


```

import matplotlib.pyplot as plt
x1=[1,2,3,4,5,6,7,8,9,10]
y1=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x1,y1,label='stars',color='green',marker='*',s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()

```

<img width="808" height="576" alt="image" src="https://github.com/user-attachments/assets/f7de1823-33dc-41c3-ad8e-e6aed08f6712" />

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x

```
<img width="472" height="39" alt="image" src="https://github.com/user-attachments/assets/d98c3026-871b-4fc1-97f1-a30b2294e452" />

```

y

```
<img width="569" height="40" alt="image" src="https://github.com/user-attachments/assets/b2f7d276-747f-4215-be42-2df39444efcd" />

```

plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graphs in 2D')
plt.savefig('Test.png')
```

<img width="714" height="576" alt="image" src="https://github.com/user-attachments/assets/8fae8546-6fa6-46ab-814a-5fc09bd188b2" />

```
y=x*x
y


```

<img width="562" height="42" alt="image" src="https://github.com/user-attachments/assets/54655e27-e86c-4ba9-85c0-aa7ca5a59792" />


```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d diagram')

```
<img width="828" height="625" alt="image" src="https://github.com/user-attachments/assets/62c4345e-82c1-4f37-925d-728dc3b647ee" />

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')

```
<img width="848" height="581" alt="image" src="https://github.com/user-attachments/assets/689cd23c-0080-4bd2-ad0b-980b823ad666" />


```
np.pi

```

<img width="283" height="43" alt="image" src="https://github.com/user-attachments/assets/b26466e7-39b9-470c-9627-2607a38014bf" />

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title('Sine wave form')
plt.plot(x,y)
plt.show()
```
<img width="739" height="558" alt="image" src="https://github.com/user-attachments/assets/352a28aa-3b8f-4254-96f7-0169c158a982" />

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()

```
<img width="731" height="537" alt="image" src="https://github.com/user-attachments/assets/9987cb35-f787-44fe-a664-5e9979cdcbf5" />

```
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.stackplot(x,y1,y2,y3,labels=['Line1','Line2','Line3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()
```

<img width="727" height="581" alt="image" src="https://github.com/user-attachments/assets/74970247-568a-4dcd-9ca5-6c41de2190eb" />


```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x = np.array([1,2,3,4,5,6,7,8,9,10])
y = np.array([2,4,5,6,7,8,8,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()

```

<img width="716" height="530" alt="image" src="https://github.com/user-attachments/assets/6ea720a5-6bc2-4fa6-9088-bb1aa2a1ad8a" />

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=['A','B','C','D','E']
plt.bar(names,values,color='green')
plt.show()
```
<img width="680" height="527" alt="image" src="https://github.com/user-attachments/assets/d2bf0078-0f2e-4443-88d1-b79cca402d67" />

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=['A','B','C','D','E']
plt.barh(names,values,color='yellowgreen')
plt.show()

```
<img width="703" height="525" alt="image" src="https://github.com/user-attachments/assets/7bc2dea4-85de-4fcd-970d-19a329d3ab7d" />


```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="723" height="580" alt="image" src="https://github.com/user-attachments/assets/fb90db5f-67c9-4c09-be15-2b38b544eb7d" />


```

x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()

```
<img width="729" height="581" alt="image" src="https://github.com/user-attachments/assets/22b68880-a41e-4476-b368-7857168d4a82" />

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()

```

<img width="710" height="583" alt="image" src="https://github.com/user-attachments/assets/dc501868-4df0-49ec-977c-a60d97d770d8" />

```
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()

```

<img width="687" height="525" alt="image" src="https://github.com/user-attachments/assets/e50797b7-60ab-4769-8b64-e3d937f513e6" />

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
<img width="821" height="445" alt="image" src="https://github.com/user-attachments/assets/16202d6d-5e7e-46cc-9804-21207a31652b" />


```

fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

![Uploading image.png…]()

```

```


# Result:

 Include your result here
