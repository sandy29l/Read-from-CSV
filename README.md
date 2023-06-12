# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of row returned is difined in pandas option settings.

### Step 4:
Check your systems maximum column with the pd.options.display.max_column statement.

### Step 5:
 Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
"""
Developed by: Santhosh L
Reg no: 212222100046
"""
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of columns",len(df.axes[1]))
```
# OUTPUT:
![Screenshot (28)](https://github.com/sandy29l/Read-from-CSV/assets/123359969/9dc9c105-9522-4b8f-b1b9-d694f4b44d38)

## RESULT:
Thus the program executed successfully for read csv file.
