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
```
#Program to find the solution for the given linear equations.
#Developed by: Mithun kumar V 
#RegisterNumber:25012629
import numpy as np
A = np.array([[1, 3], [2, 5]])
B = np.array([5, -3])
solution = np.linalg.solve(A, B)
print(solution)
```
<img width="1292" height="725" alt="image" src="https://github.com/user-attachments/assets/27574fd6-62b6-4a21-9b18-bb031487d1c2" />


## Output:
<img width="1307" height="312" alt="image" src="https://github.com/user-attachments/assets/ddb83e3d-16d1-4e91-b7a1-630101d106cb" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

