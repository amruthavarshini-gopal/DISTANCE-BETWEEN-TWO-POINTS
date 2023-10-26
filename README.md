# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance between two  points
## ALGORITHM:
### Step 1:
Define a function with suitable name 
### Step 2: 
Assign the given values to the four variables
### Step 3: 
Substitute the values in the distance formula
![Alt text](formula.JPG)
### Step 4:
Return the value of distance 
### Step 5: 
Store the value in another variable and call the function
### Step 6:
Round it off the variable upto two decimal point and print the statement
### Step 7:
End the program
### PROGRAM:
```
# Program to find the distance between two points.
# Developed by:Amruthavarshini Gopal
# RegisterNumber:23000851
def distance():
    x_1=4
    x_2=10
    y_1=2
    y_2=6
    d=((x_2-x_1)**2+(y_2-y_1)**2)**0.5
    return d
ans=distance()
print(round(ans,2))
```
  
### OUTPUT:
![Alt text](<distance between two points.png>)

### RESULT:
Thus the distance between two points are successfully executed
