## DATE:
# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
def circulate():

    lst=eval(input())
    
    n=int(input())
    
    result=lst[n:]+lst[:n]
    
    print("After circulating the values are:",result)
    
## Output:
![Screenshot 2024-08-27 150818](https://github.com/user-attachments/assets/f72cf22a-381b-44e0-b7b9-c4f0b594d080)
## Result:
The output for circulate the values of n variables is successfull.
