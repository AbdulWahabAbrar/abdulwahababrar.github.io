---
layout: post
title:  "File Handling and using Loops to solve cumbersome tasks"
category: Blog
---


File handling is an important part of any Data Scientist, you import files in the form of .csv or .txt or something, To be able to work with file handling you must be perfect for basic Pythonic things. Datasets are often represented in files that can be downloaded and manipulated.

1. When we assign the *open()* function to a variable, actually allows that variable to refer to that file but does not store content of the file but acts as file object interface.

2. *read()* method returns string representation of the file.

3. *split()* function is **used for strings only** to separate the values.

4. Crazy thing of Python is **:**, which yields *from:to* format of the lists and *to* is actually **to-1**.

5. When you ask Python interpreter to do like,
```
cities = ["Austin", "Dallas", "Houston"]
    for city in cities:
        print(city)
```
it'll assign the first index of cities list to city and prints is as a city when print() is run, as we are using *forever* loop so it'll give output as all the city names!

6. Open a file in "r", make it a string as .read() thing, make an empty list and using for loop iterate then print first five values in the .csv
```
f = open("crime.rates.csv", "r")
g = f.read()
rows = g.split('\n')
final_data = []
for i in rows:
    splitter = i.split(",")
    final_data.append(splitter)
    continue
print(final_data[0:5])
```
and this is how I used the below code in funny, my own way to read and print data of .csv file :P
```
kholo = open('crime_rates.csv', 'r')
readkaroinstring = kholo.read()
rows = readkaroinstring.split('\n')
final_data = []
for girgira in rows:
    commahatau = girgira.split(',')
    final_data.append(commahatau)
    continue #loop ku khatam karke next line pe jaata
print(final_data[0:5])
```
7. Using two dimensional or double bracket notation returns a specified one value, like If I want only city names from the final_list I wrote the below code.
```
print(five_elements)
cities_list = []
cities_list.append(five_elements[0][0])
cities_list.append(five_elements[1][0])
cities_list.append(five_elements[2][0])
cities_list.append(five_elements[3][0])
cities_list.append(five_elements[4][0])
```

8. [PROJECT] Separating Crime_rates from city_names:
```
f = open('crime_rates.csv', 'r')
data = f.read()
rows = data.split('\n')
print(rows[0:5])
int_crime_rates = []
for KhaliInt in rows:
    splitter = KhaliInt.split(",")
    cm = int(splitter[1])
    int_crime_rates.append(cm)
```    
**int()** is a function which converts the listings into integer!
