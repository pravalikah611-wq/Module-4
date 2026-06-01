# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program:

import math

class cse:
    def mech(self, radius):
        area = math.pi * radius * radius
        return area

# Taking input from user
r = float(input("Enter the radius of the circle: "))

# Creating object
obj = cse()

# Calculating area
result = obj.mech(r)

print("Area of the circle is:", result)
<img width="1591" height="577" alt="image" src="https://github.com/user-attachments/assets/c151d0a1-3689-4c28-bca8-758782789cfd" />

 

## Output:
<img width="1591" height="577" alt="image" src="https://github.com/user-attachments/assets/2dc10145-f975-43ec-b99a-9415e0fa1774" />


## Result:
The program successfully calculates the area of a circle using the radius provided by the user, by applying the formula πr2 inside the class cse and method mech, and displays the computed area.
