#  NumPy Array Operations

## 📌 Project Overview

This project demonstrates basic mathematical operations using NumPy arrays in Python.

Two NumPy arrays are created, and four mathematical operations are performed: addition, subtraction, multiplication, and division.

This project was completed as part of **Task 12 (Level 1, Day 12)** of the AI & ML Internship at **Veda Technology** using **Google Colab**.

## 🎯 Objective

To understand how NumPy performs mathematical operations on arrays and learn the basics of element-wise array calculations.

## 🛠️ Technologies Used

- Python
- NumPy
- Google Colab
- GitHub

## 📚 Project Implementation

### 1. Import NumPy

The NumPy library is imported to perform numerical operations.

```python
import numpy as np
```

### 2. Create Two NumPy Arrays

Two arrays containing numerical values are created.

```python
array1 = np.array([10, 20, 30, 40, 50])
array2 = np.array([2, 4, 5, 8, 10])
```

### 3. Addition

Adds corresponding elements of both arrays.

```python
addition = array1 + array2
```

**Output:**
```text
[12 24 35 48 60]
```

### 4. Subtraction

Subtracts corresponding elements of the second array from the first array.

```python
subtraction = array1 - array2
```

**Output:**
```text
[ 8 16 25 32 40]
```

### 5. Multiplication

Multiplies corresponding elements of both arrays.

```python
multiplication = array1 * array2
```

**Output:**
```text
[ 20  80 150 320 500]
```

### 6. Division

Divides corresponding elements of the first array by the second array.

```python
division = array1 / array2
```

**Output:**
```text
[5. 5. 6. 5. 5.]
```

## 📊 Summary of Results

| Operation | Result |
|---|---|
| Addition | `[12, 24, 35, 48, 60]` |
| Subtraction | `[8, 16, 25, 32, 40]` |
| Multiplication | `[20, 80, 150, 320, 500]` |
| Division | `[5, 5, 6, 5, 5]` |

## ⚡ Key Concept: Element-wise Operations

NumPy performs mathematical operations element by element when two arrays have compatible shapes.

Instead of using separate loops to process each value, NumPy allows operations to be performed directly on entire arrays.

This makes numerical calculations simpler and more convenient.

## 💻 How to Run the Project

This project is developed using **Google Colab**.

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook `Array_Operations.ipynb`.
3. Run each code cell in sequence.
4. View the results of addition, subtraction, multiplication, and division.

**Note:** NumPy is available by default in Google Colab, so no separate installation is normally required.

## 📁 Project Structure

```text
NumPy-Array-Operations/
│
├── Array_Operations.ipynb
└── README.md
```

## 📈 Learning Outcomes

Through this task, I learned how to:

- Import and use the NumPy library.
- Create NumPy arrays.
- Perform addition and subtraction on arrays.
- Perform multiplication and division on arrays.
- Understand element-wise mathematical operations.
- Execute Python code using Google Colab.

## 🏁 Conclusion

This task helped me understand how NumPy makes mathematical operations on arrays simple and efficient. I gained practical experience performing addition, subtraction, multiplication, and division using Python.

## 👨‍💻 Internship Details

- **Organization:** Veda Technology
- **Track:** AI & ML
- **Task:** Task 12 — NumPy Array Operations
- **Level:** Level 1
- **Day:** Day 12
- **Platform:** Google Colab

---

⭐ This project is part of my AI & ML learning journey at Veda Technology.
