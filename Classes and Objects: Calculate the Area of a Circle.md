# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
~~~
class cse:
    def mech(r):
        a=3.1416*(r**2)
        a=round(a,2)
        print("Area of circle:",a)
r=int(input())
cse.mech(r)
~~~

## Output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/3a1abd0b-6eec-428e-9f8a-4042eb2addaa" />

## Result
Thus, the program has been executed successfully.
