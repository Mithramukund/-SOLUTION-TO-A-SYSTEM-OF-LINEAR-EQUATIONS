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
#Program to find the solution for the given linear equations.
#Developed by: mithra mukundaa
#RegisterNumber:22005703
import numpy as np

m_list = [[1, 3], [2, 5]]
A = np.array(m_list)
inv_A = np.linalg.inv(A)
B = np.array([5, -3])
X = np.linalg.inv(A).dot(B)

print(X)
```
## Output:
![m1](https://user-images.githubusercontent.com/121608770/213072158-18ed5016-9029-4af0-9a6d-fe452bd41efe.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

