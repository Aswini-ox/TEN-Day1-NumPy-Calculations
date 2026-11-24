# TEN AI Internship – Day 1: NumPy Vector Calculations

> **Internship Domain:** Artificial Intelligence  
> **Task:** Day 1 – NumPy Vector Calculations  
> **Notebook:** `TEN_Day1_NumPy_Vector_Calculations.ipynb`

---

## 👩‍💻 Student Details

| Field | Details |
|---|---|
| **Name** | Aswini R I |
| **TEN Employee ID** | TEN/AI/17271616 |
| **College** | V.S.B. College of Engineering Technical Campus |
| **Department** | B.E. Computer Science and Engineering |
| **Internship Domain** | Artificial Intelligence |
| **Task** | Day 1 – NumPy Vector Calculations |

---

## 📌 Project Overview

This project is the Day 1 task of the TEN AI Internship. It is a hands-on introduction to **NumPy**, the core numerical computing library behind most Python-based Artificial Intelligence and Machine Learning workflows. The notebook demonstrates how vectors, matrices and multi-dimensional arrays are created and manipulated, covering the fundamental linear algebra operations that later underpin topics such as neural networks, data preprocessing and model training.

## 🎯 Objective

- Understand how to create and work with NumPy arrays (vectors, matrices and 3D arrays).
- Perform element-wise vector arithmetic and scalar multiplication.
- Compute the dot product of two vectors.
- Apply matrix multiplication and transpose.
- Inspect array properties such as shape, number of dimensions and sum.
- Calculate the determinant of a square matrix using `numpy.linalg`.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Python 3.11** | Programming language |
| **NumPy** | Array creation and numerical / linear algebra operations |
| **JupyterLab** | Interactive notebook environment |

## ⚙️ Operations Performed

| # | Operation | NumPy Function / Syntax |
|---|---|---|
| 1 | Vector creation | `np.array([...])` |
| 2 | Vector addition and subtraction | `A + B`, `A - B` |
| 3 | Scalar multiplication | `A * 2` |
| 4 | Dot product | `np.dot(A, B)` |
| 5 | Matrix creation and multiplication | `np.dot(M1, M2)` |
| 6 | Matrix transpose | `M1.T` |
| 7 | Three-dimensional array operations | `np.array([[[...]]])` |
| 8 | Array shape, dimensions and sum | `arr.shape`, `arr.ndim`, `np.sum(arr)` |
| 9 | Determinant calculation | `np.linalg.det(M1)` |

## 🧾 Sample Output

```text
Vector A: [2 4 6]
Vector B: [1 3 5]

Addition: [ 3  7 11]
Subtraction: [1 1 1]
Scalar Multiplication: [ 4  8 12]
Dot Product: 44

Matrix 1:
 [[1 2]
 [3 4]]
Matrix 2:
 [[5 6]
 [7 8]]
Matrix Multiplication:
 [[19 22]
 [43 50]]
Transpose:
 [[1 3]
 [2 4]]

3D Array:
 [[[1 2]
  [3 4]]

 [[5 6]
  [7 8]]]
Array Shape: (2, 2, 2)
Array Dimensions: 3
Array Sum: 36
Determinant: -2.0000000000000004

All NumPy operations completed successfully!
```

> The determinant is printed as `-2.0000000000000004` instead of exactly `-2.0` because NumPy computes it using floating-point arithmetic (LU decomposition), which introduces a very small rounding error.

## ✅ Conclusion

All the planned NumPy operations executed successfully. The task gave practical experience with vector arithmetic, dot products, matrix multiplication, transpose, 3D arrays, array properties and determinant calculation. These building blocks are used throughout AI and Machine Learning, so this exercise forms a solid base for the upcoming internship tasks.

## ▶️ How to Run the Notebook

1. **Install Python 3.11** (or use Anaconda / Miniconda).
2. **Install the required packages:**
   ```bash
   pip install numpy jupyterlab
   ```
3. **Launch JupyterLab** from the folder containing the notebook:
   ```bash
   jupyter lab
   ```
4. **Open** `TEN_Day1_NumPy_Vector_Calculations.ipynb` from the file browser.
5. **Run all cells:** choose **Run → Run All Cells** (or press `Shift + Enter` on each cell).
6. Compare the printed results with the sample output above.

## 📁 Repository Contents

```text
├── TEN_Day1_NumPy_Vector_Calculations.ipynb         # Notebook with code and output
├── TEN_Day1_NumPy_Vector_Calculations_Report.pdf    # Formal task report
└── README.md                                        # Project documentation
```

---

*Prepared by Aswini R I (TEN/AI/17271616) as part of the TEN AI Internship – Day 1 task documentation.*
