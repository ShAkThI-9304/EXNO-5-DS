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
### Line
 ```python
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
![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/c3b67192-19a4-4305-8b63-93671cc3ca71)

![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/216928ba-71c0-47c1-a47e-4ca8e26eec10)


### Bar graph
```python
x=[10,20,30,40,50]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()

x=[14,30,25,6,20]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()
```
![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/f0d9c08f-acce-495e-9f29-77fe62332804)

![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/1e7c8786-89de-4778-8e6d-484bd69d3bb2)

### Scatterplot
```python
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

![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/8f54ce72-bba6-42e8-ba5b-9259032223f6)


![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/26cebaf4-e4fd-4ee4-9ff7-86ff38cecfd6)

### Histogram
```python
ages=[2,5,70,40,30,45,50,45,43,40]
range=(0,80)
bin=10
plt.hist(ages,bin,range,color='green',histtype='bar',rwidht=0.8)
plt.xlabel('ages')
plt.ylabel('No of people')
plt.legend()
plt.title('Histogram')
plt.show()

x=[2,1,6,4,2,4,8,9,4,2,10]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```

![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/a1c2f3fb-a08e-417e-83e2-a0a2c7f5aeed)


![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/61d28c92-f056-4a36-b784-716d5d7799d1)

### Pie chart
```python
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

![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/e3870776-ea96-4522-8b0f-2887755b37aa)


![image](https://github.com/MeethaPrabhu/EXNO-5-DS/assets/119401038/81a59656-1a40-467b-860a-a42f93e1ebae)


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
