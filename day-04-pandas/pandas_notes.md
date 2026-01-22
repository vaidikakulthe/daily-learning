# Day 4 Pandas Basics

## What I learned today
- Series works like one column
- DataFrame works like full table
- DataFrame is made using dictionary
- Pandas is used for data analysis

## Series
- One-dimensional data structure
- Stores data with index
- Similar to a single column

Example:
```python 
import pandas as pd
s = pd.Series([10, 20, 30])
print(s)
```

## DataFrame
- Two-dimensional table
- Rows and columns
- Collection of Series

Example:
```python
import pandas as pd
df = pd.DataFrame({
    "Name": ["A", "B"],
    "Age": [20, 22]
})
print(df)



