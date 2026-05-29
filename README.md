# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: Start the program.
### Step 2: Get the list of values from the user.
### Step 3: Get the value from the user for the number of rotation
### Step 4: Using the slicing concept, rotate the list.
### Step 5: Display the rotated list.
### Step 6: Stop the program.
## Program:
```
def rotate_list(lst, n):
    return lst[-n:] + lst[:-n]

values = list(map(int, input("Enter the list values: ").split()))
n = int(input("Enter number of rotations: "))

result = rotate_list(values, n)

print("Rotated List:", result)
```

## Output:
<img width="715" height="179" alt="image" src="https://github.com/user-attachments/assets/a355f4ac-f60c-4415-a0b7-0c034a337871" />


## Result:
