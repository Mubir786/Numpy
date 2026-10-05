# 🔢 NumPy Learning Journey

Welcome to my **NumPy Learning Journey** repository! 🚀

This repository documents my journey of learning **NumPy (Numerical Python)**, starting from the fundamentals and gradually progressing toward numerical computing, array manipulation, mathematical operations, and data processing.

The goal of this repository is to build a strong understanding of NumPy and develop the skills required for **Data Science, Machine Learning, Artificial Intelligence, and Digital Image Processing**.

---

## 🎯 Learning Goals

My goals are to learn how to efficiently work with numerical data and use NumPy for:

* 🔢 Numerical Computing
* 📊 Data Analysis
* 🤖 Machine Learning
* 🧠 Artificial Intelligence
* 🖼️ Digital Image Processing
* 📈 Mathematical & Statistical Operations
* 🔬 Research & Scientific Computing

---

## 📚 Topics Covered

### 1. Introduction to NumPy

* What is NumPy?
* Why NumPy is used
* Installing NumPy
* Importing NumPy
* NumPy vs Python Lists

Example:

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])

print(arr)
```

---

### 2. NumPy Arrays

* Creating NumPy arrays
* 1D arrays
* 2D arrays
* Multi-dimensional arrays
* Array properties
* Array data types

Important properties:

```python
arr.ndim
arr.shape
arr.size
arr.dtype
```

---

### 3. Array Creation Methods

Learning different ways to create arrays:

* `np.array()`
* `np.zeros()`
* `np.ones()`
* `np.empty()`
* `np.full()`
* `np.arange()`
* `np.linspace()`
* `np.eye()`

Example:

```python
arr = np.arange(1, 11)

print(arr)
```

---

### 4. Indexing & Slicing

* Array indexing
* Negative indexing
* Array slicing
* 2D array indexing
* Row selection
* Column selection
* Multi-dimensional slicing

Example:

```python
arr = np.array([10, 20, 30, 40, 50])

print(arr[0])
print(arr[1:4])
```

---

### 5. Reshaping Arrays

* `reshape()`
* `flatten()`
* `ravel()`
* Changing array dimensions
* Understanding rows and columns

Example:

```python
arr = np.arange(1, 10)

matrix = arr.reshape(3, 3)

print(matrix)
```

---

### 6. Array Operations

Learning mathematical operations on arrays:

* Addition
* Subtraction
* Multiplication
* Division
* Power
* Modulus

Example:

```python
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

print(a + b)
print(a * b)
```

---

### 7. Mathematical Functions

* `np.sqrt()`
* `np.square()`
* `np.power()`
* `np.abs()`
* `np.exp()`
* `np.log()`
* `np.sin()`
* `np.cos()`

---

### 8. Statistical Functions

* `np.mean()`
* `np.median()`
* `np.std()`
* `np.var()`
* `np.min()`
* `np.max()`
* `np.sum()`
* `np.prod()`

Example:

```python
data = np.array([10, 20, 30, 40, 50])

print(np.mean(data))
print(np.max(data))
print(np.min(data))
```

---

### 9. Random Numbers

Learning NumPy's random module:

* Random numbers
* Random integers
* Random arrays
* Random distributions
* Random seeds

Example:

```python
numbers = np.random.randint(1, 100, 10)

print(numbers)
```

---

### 10. Boolean & Conditional Operations

* Boolean arrays
* Comparison operations
* Conditional filtering
* `np.where()`

Example:

```python
arr = np.array([10, 20, 30, 40, 50])

result = arr[arr > 25]

print(result)
```

---

### 11. Array Manipulation

* `reshape()`
* `resize()`
* `transpose()`
* `flatten()`
* `ravel()`
* `concatenate()`
* `stack()`
* `split()`

---

### 12. Linear Algebra

Introduction to NumPy's linear algebra capabilities:

* Matrix multiplication
* Dot product
* Transpose
* Determinant
* Inverse
* Eigenvalues
* Eigenvectors

Example:

```python
A = np.array([[1, 2],
              [3, 4]])

B = np.array([[5, 6],
              [7, 8]])

result = np.dot(A, B)

print(result)
```

---

## 🚧 Upcoming Topics

* Advanced Array Manipulation
* Broadcasting
* Vectorization
* Advanced Indexing
* Masking
* Linear Algebra
* Fourier Transform
* Numerical Methods
* Image Processing with NumPy
* NumPy for Machine Learning
* Performance Optimization

---

## 📂 Repository Structure

```text
NumPy-Learning/
│
├── 01_Introduction/
│   ├── numpy_intro.py
│   └── numpy_vs_lists.py
│
├── 02_Arrays/
│   ├── arrays.py
│   └── array_properties.py
│
├── 03_Array_Creation/
│   ├── zeros.py
│   ├── ones.py
│   ├── arange.py
│   └── linspace.py
│
├── 04_Indexing_Slicing/
│   ├── indexing.py
│   └── slicing.py
│
├── 05_Reshaping/
│   ├── reshape.py
│   └── flatten.py
│
├── 06_Array_Operations/
│   └── operations.py
│
├── 07_Mathematical_Functions/
│   └── math_functions.py
│
├── 08_Statistics/
│   └── statistics.py
│
├── 09_Random/
│   └── random.py
│
├── 10_Array_Manipulation/
│   └── manipulation.py
│
├── 11_Linear_Algebra/
│   └── linear_algebra.py
│
├── Practice/
│   └── ...
│
├── Projects/
│   └── ...
│
└── README.md
```

> The repository structure may evolve as I learn more NumPy concepts.

---

## 🧪 Practice

I regularly solve exercises to strengthen my NumPy skills.

Practice includes:

* Creating arrays
* Indexing and slicing
* Reshaping arrays
* Mathematical operations
* Statistical calculations
* Random number generation
* Array filtering
* Matrix operations
* Numerical problems

---

## 🚀 Projects

As I progress, I will add practical NumPy projects.

| Project                 | Description                          | Status     |
| ----------------------- | ------------------------------------ | ---------- |
| 🔢 Array Calculator     | Perform numerical operations         | 🔄 Planned |
| 📊 Statistical Analysis | Analyze numerical datasets           | 🔄 Planned |
| 🧮 Matrix Operations    | Perform matrix calculations          | 🔄 Planned |
| 🖼️ Image Processing    | Manipulate images using NumPy arrays | 🔄 Planned |
| 📈 Numerical Analysis   | Solve numerical problems             | 🔄 Planned |

---

## 📈 Learning Progress

* [x] NumPy Introduction
* [x] NumPy Arrays
* [x] Array Properties
* [x] Array Creation
* [x] Indexing
* [x] Slicing
* [x] Reshaping
* [x] Basic Array Operations
* [x] `arange()`
* [x] `linspace()`
* [ ] Broadcasting
* [ ] Advanced Indexing
* [ ] Advanced Array Manipulation
* [ ] Linear Algebra
* [ ] Fourier Transform
* [ ] Image Processing
* [ ] NumPy Optimization
* [ ] NumPy Projects

> This checklist will be updated as my learning progresses.

---

## 🛠️ Tools & Technologies

Currently using:

* 🐍 Python
* 🔢 NumPy
* 🐼 Pandas
* 📊 Matplotlib
* 📓 Jupyter Notebook
* 💻 VS Code
* 🐙 Git & GitHub

---

## 🔗 My Learning Path

NumPy is part of my broader Python and Data Science learning journey.

```text
🐍 Python
   │
   ├── 🔢 NumPy
   │       │
   │       ├── Numerical Computing
   │       ├── Array Manipulation
   │       └── Mathematical Operations
   │
   ├── 🐼 Pandas
   │       └── Data Analysis
   │
   ├── 📊 Matplotlib
   │       └── Data Visualization
   │
   ├── 🤖 Machine Learning
   │
   └── 🧠 Artificial Intelligence
```

---

## 🖼️ NumPy & Digital Image Processing

NumPy is particularly important for my future work in **Digital Image Processing** because images can be represented as numerical arrays.

For example:

```text
Image
  ↓
Pixels
  ↓
Numerical Values
  ↓
NumPy Array
  ↓
Image Processing
```

This will allow me to explore operations such as:

* Image representation
* Pixel manipulation
* Image resizing
* Brightness adjustment
* Contrast enhancement
* Filtering
* Transformations
* Image analysis

---

## 💡 Learning Philosophy

> **Learn → Practice → Experiment → Debug → Build → Improve**

I believe that understanding NumPy requires more than memorizing functions. The goal is to understand **how numerical data is represented, manipulated, and processed using arrays**.

This repository contains my exercises, experiments, notes, and projects as I progress.

---

## 🎓 Future Direction

After developing a strong foundation in NumPy, I plan to apply it to:

* 📊 Data Science
* 🤖 Machine Learning
* 🧠 Artificial Intelligence
* 🖼️ Computer Vision
* 🔬 Digital Image Processing
* 📈 Scientific Computing
* 🔍 Research Projects

---

## 👨‍💻 About Me

I am a **Computer Science graduate** currently expanding my skills in **Python, Data Science, and Artificial Intelligence**.

My interests include:

* Artificial Intelligence
* Machine Learning
* Computer Vision
* Data Science
* Digital Image Processing
* Web Development
* AI-powered Applications

---

## 📫 Connect With Me

* **GitHub:** [Mubir786](https://github.com/Mubir786)
* **LinkedIn:** [Mubir Hussain](https://www.linkedin.com/in/mubir-hussain-669788250/)
* **Portfolio:** [My Portfolio](https://mubir-portfolio.netlify.app/)

---

## ⭐ Support

If you find this repository useful, feel free to **star ⭐ the repository** and follow my learning journey.

---

### 🔢 Learn Numbers. Understand Arrays. Build with NumPy.

**Learning NumPy one array at a time. 🚀**
