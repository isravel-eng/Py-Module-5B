# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```py
import pandas as pd

student_data1 = {
    'name': ['Alice', 'Bob', 'Charlie'],
    'score': [85, 90, 95],
    'grade': ['B', 'A', 'A']
}
df1 = pd.DataFrame(student_data1)

student_data2 = {
    'name': ['David', 'Eva'],
    'score': [88, 92],
    'grade': ['B+', 'A']
}
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0)

print(combined_df)
```

## Output
<img width="402" height="583" alt="image" src="https://github.com/user-attachments/assets/5722ac5b-8d9f-49d2-9cc8-fd0bbb350982" />

## Result
Successfullly wrote a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.
