# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To Write Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary'
---

### ALGORITHM

1. Begin the program.  

2.Import the math module to access the constant pi.

3.Create a class named pen.

4.Define a method stationary(self, r) inside the pen class that:

Calculates the area of the circle using the formula:

Area=π×r2

Prints the result formatted to two decimal places.

5.Prompt the user to input the radius of the circle.

6.Convert the input to an integer.

7.Create an instance of the class pen and assign it to variable p.

8.Call the stationary method with the input radius.

9.End the program.


 PROGRAM

 import math

class pen:

    def __init__(self, radius):
    
        self.radius = radius

    def stationary(self):
    
        return math.pi * self.radius ** 2


radius = float(input())


circle = pen(radius)


area = circle.stationary()

print(f"Area of circle: {area:.2f}")


OUTPUT

![image](https://github.com/user-attachments/assets/a9e7de9c-a3f2-46df-a45a-ea889e9c3768)


 RESULT

Thus the  Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary' was implemented and executed successfully.



