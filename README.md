# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```python
Program to find the solution for the given linear equations.
Developed by: harini.m.d
RegisterNumber: 22001980
import numpy as np
A=np.array([[1, -3], [3, 1]]) 
B=np.array([0, 10]) 
lin=np.linalg.solve(A, B) 
print(lin) 
```


## Output:
![Screenshot from 2022-09-20 20-47-26](https://user-images.githubusercontent.com/113497680/191298375-dc4ea49c-b0ef-463e-a3d7-cc292b090676.png)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program
