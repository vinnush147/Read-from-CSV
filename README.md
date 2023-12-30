# Read-from-CSV

## AIM:
To write a program to read a csv file.
## ALGORITHM: 
### Step 1:
Import pands module as pd.
### Step 2:
Read a csv file name cars.csv.
### Step 3:
Print the first five rows and last five rows.
### Step 4:
Print the length of the rows and columns.
### Step 5:
End the program.
## PROGRAM:
```python
# Program to read a csv file.
# Developed by: Vinnush kumar L S
# Reference number: 23012349.
import pandas as pd
df = pd.read_csv("cars.csv")
print(df.head())
print(df.tail())
print("Rows", len(df.axes[0]))
print("Columns", len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/vinnush147/Read-from-CSV/assets/147139234/085ccf19-891c-4bac-ba3e-ff414d22bd93)
![f3fd455b-7a6d-4ed1-a981-b6711aa5f832](https://github.com/vinnush147/Read-from-CSV/assets/147139234/7bd00513-7754-4760-9e64-474ed2b32dbc)



# csv file:
![image](https://github.com/vinnush147/Read-from-CSV/assets/147139234/15d589bd-b445-4b02-be05-f1f12a5f9a1b)


## RESULT:
Thus the program is written to read a csv file
