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
```
import pandas as pd
a=pd.DataFrame(eval(input()))
b=pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(a)
print("-------------------------------------")
print(b)
print()
print("Join the said two dataframes along columns:")
c=pd.concat([a,b],axis=1)
print(c)
```

## Output
<img width="1174" height="753" alt="image" src="https://github.com/user-attachments/assets/cba6cca9-66f3-4d6a-86cd-e61446191bd9" />


## Result
