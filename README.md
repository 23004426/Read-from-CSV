# Read-from-CSV

## AIM:
To read from CSV file
## ALGORITHM:
### Step 1:Import pandas as pd.
### Step 2: Read the CSV file using read_csv method.
### Step 3: Use head and tail method to get the required contents from the file. 
### Step 4: Use len() method to get the number of rows and columns
### Step 5: Print the output.

## PROGRAM:
```
Developed by: Tirupathi Jayadeep
Ref.no:23004426
import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-25 121555](https://github.com/23004426/Read-from-CSV/assets/144979327/27924e89-add4-44e6-94cb-4d95596265df)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
