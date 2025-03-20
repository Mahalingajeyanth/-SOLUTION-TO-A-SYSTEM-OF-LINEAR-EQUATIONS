# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step 1: 
Import the numpy module to use the built-in functions for calculation
Step 2: 
Prepare the lists from each linear equations and assign in np.array()
Step 3: 
Using the np.linalg.solve(), we can find the solutions.
Step 4:
End the program
```
## Program:
```
Developed by: M.Mahalakshmi
Register Number : 212224230148
```
```
import numpy as np
A = np.array([[1, -3],  
              [3, 1]])  

B = np.array([0, 10])  
solution = np.linalg.solve(A, B)
x, y = solution
print(f"[{int(x)}. {round(y)}.]")
```

## Output:
![alt text](<Screenshot 2025-03-13 141445.png>)

![Screenshot 2025-03-03 082450](https://github.com/user-attachments/assets/5ba18f96-3634-48d5-97ad-ffe90e595b28)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

