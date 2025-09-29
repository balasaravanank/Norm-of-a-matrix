<img width="1824" height="1546" alt="Screenshot 2025-09-29 143818" src="https://github.com/user-attachments/assets/8141c16d-c8ac-43f3-8d4c-6a087a3188c6" /># Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: BALA SARAVANAN K
# Developed By: 212224230031
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))

ans= np.linalg.norm(mat,1)
norm_of_matrix= "{:.2f}".format(ans)

print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)

print(norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)

print("%.2f"%(ans))






```
## Output:
### 1-Norm of a Matrix
<img width="1680" height="1577" alt="Screenshot 2025-09-29 143740" src="https://github.com/user-attachments/assets/f29e1715-05c9-40da-9eda-6543bd204e68" />

### 2-Norm of a Matrix
<img width="1793" height="1543" alt="Screenshot 2025-09-29 143800" src="https://github.com/user-attachments/assets/cfcc968e-39e1-435b-a792-00e0665e08c0" />

### Infinity Norm of a Matrix
<img width="1824" height="1546" alt="Screenshot 2025-09-29 143818" src="https://github.com/user-attachments/assets/f6322d4a-0db5-4b48-a881-38cfc8bfcbf1" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
