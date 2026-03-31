
# 📊 Categorical Data Analysis Using Python

## 🧪 Experiment No. 11

### 👩‍🎓 Student Information
- **Name:** Gayatri Bhosale  
- **PRN:** 25070123033  

---

## 🎯 Objective
To perform **categorical data analysis using Python** and understand how to inspect and analyze category-based data using the **Pandas library**.

---

## 🛠 Tools & Technologies
- 🐍 Python  
- 📊 Pandas Library  
- 💻 Jupyter Notebook  

---

## 📂 Dataset Description

The dataset contains **Order IDs** and their corresponding **Product Categories**.

| Order ID | Category |
|---------|----------|
| 01 | Furniture |
| 02 | Office Supplies |
| 03 | Furniture |
| 04 | Technology |
| 05 | Technology |
| 06 | Furniture |
| 07 | Office Supplies |
| 08 | Technology |
| 09 | Furniture |
| 10 | Office Supplies |

---

# 🔎 Data Analysis Steps

## 1️⃣ Frequency Count
Counts how many orders belong to each category.

```python
df['Category'].value_counts()
```

✅ Helps identify **which category appears most frequently**.

---

## 2️⃣ Unique Values
Displays all unique category names present in the dataset.

```python
df['Category'].unique()
```

✅ Useful for identifying **different category types in the dataset**.

---

## 3️⃣ Number of Unique Categories
Counts the total number of unique categories.

```python
df['Category'].nunique()
```

✅ Helps determine **the diversity of categories**.

---

## 📈 Sample Output

Example frequency result:

| Category | Count |
|---------|------|
| Furniture | 4 |
| Technology | 3 |
| Office Supplies | 3 |

---

## 📚 Conclusion

- Python and Pandas make **categorical data analysis easy and efficient**.
- Functions like `value_counts()`, `unique()`, and `nunique()` help analyze categorical variables quickly.
- This analysis helps in **understanding patterns and category distribution in datasets**.

---

## 🚀 Future Improvements
- 📊 Data visualization using **Matplotlib** or **Seaborn**
- 📉 Category comparison charts
- 📁 Analysis using larger datasets

---

⭐ *Categorical Data Analysis is an important step in data preprocessing and exploratory data analysis (EDA).*

