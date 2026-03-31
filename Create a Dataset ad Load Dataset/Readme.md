# 📊 Create and Load Dataset using Python

👩‍💻 **Author:** Gayatri Bhosale  
🆔 **PRN:** 25070123033  

---

## 🎯 Objective
To **create a dataset and load it using Python and Pandas**, and perform basic dataset operations.

---

## 🛠️ Tools & Technologies
- 🐍 Python  
- 📦 Pandas Library  
- 💻 Jupyter Notebook  

---

## 📂 Dataset Creation

We first create a dataset using a **Python dictionary** and convert it into a **Pandas DataFrame**.

```python
import pandas as pd

data = {
    "Roll_no": [101,102,103,104,105],
    "Gender": ["Female","Male","Female","Male","Male"],
    "Department": ["CSE","Mechanical","ENTC","IT","ENTC"]
}

df = pd.DataFrame(data)
print(df)


# 📂 Dataset Creation

A dataset of students is created using a **Python dictionary** and converted into a **Pandas DataFrame**.

### Dataset Columns
- Roll_no
- Gender
- Department
- CGPA
- Year

### Example Code

```python
import pandas as pd

data = {
    "Roll_no":[101,102,103,104,105],
    "Gender":["Female","Male","Female","Male","Male"],
    "Department":["CSE","Mechanical","ENTC","IT","ENTC"],
    "CGPA":[8.2,7.5,9.1,6.8,8.7]
}

df = pd.DataFrame(data)
df.to_csv("student.csv", index=False)

print(df)
```

---

# ➕ Adding a New Column

A new column **Year** is added to the dataset.

```python
df["Year"] = ["First Year","Second Year","Final Year","Third Year","Second Year"]
df
```

---

# 🔍 Dataset Inspection

Different functions are used to inspect the dataset.

## 1️⃣ Shape of Dataset
Shows number of **rows and columns**.

```python
df.shape
```

---

## 2️⃣ Size of Dataset
Shows **total number of elements** in dataset.

```python
df.size
```

---

## 3️⃣ Dataset Information
Displays **column names, data types and non-null values**.

```python
df.info()
```

---

## 4️⃣ Statistical Summary
Displays **mean, min, max, std deviation** for numeric columns.

```python
df.describe()
```

---

# 📑 Accessing Data

### Access a Specific Column

```python
df["Department"]
```

### Access a Specific Row

```python
df.loc[2]
```

---

# 🔎 Data Types of Columns

To find the **data type of each column**:

```python
df.dtypes
```

---

# 📈 Output

The dataset contains **student academic information** such as roll number, department, gender, CGPA and year.

This experiment demonstrates:

- Dataset creation
- Saving dataset to CSV
- Loading dataset
- Dataset inspection
- Accessing rows and columns
- Understanding data types

---

# ✅ Conclusion

In this experiment, a **student dataset was created and analyzed using Pandas**.  
Various dataset inspection techniques like **shape, size, info, describe, and data access methods** were successfully performed.

---

⭐ This project demonstrates **basic dataset handling and inspection in Python for data analysis.**
