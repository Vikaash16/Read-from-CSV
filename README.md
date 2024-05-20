# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: Vikaash P
#Register Number: 212223240180

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/Vikaash16/Read-from-CSV/assets/139218414/ea53ea80-7e12-44ba-9eaa-63b020d1e1c5)


## RESULT:
Thus the program is written to read the csv file.
