# Python for Data Science, AI & Development

This Course is provided by **IBM** on Coursera   
**Instructor:** [Joseph Santarcangelo](https://www.coursera.org/instructor/~28511493)  
This repository contains notes, code examples, and exercises from the Coursera course Python for Data Science, AI & Development offered by IBM. The course provides a comprehensive introduction to Python programming with a focus on applications in data science, artificial intelligence, and software development.

---

## Introduction to Python

### Who Uses Python?

- Python is the most widely used and popular programming language in data science.
- According to the 2019 Kaggle survey, 75% of data scientists worldwide regularly use Python.
- Glassdoor reported that over 75% of data science job listings in 2019 included Python.
- Python is recommended as the first programming language for aspiring data scientists.

### Why Use Python?

- Python has clear and readable syntax, making it easy to write and understand.
- It allows writing programs with less code compared to many other languages.
- It has a huge global community with extensive documentation and resources.
- Suitable for beginners and experienced programmers alike.

### Applications of Python

Python is widely used in:
- Data Science
- Artificial Intelligence (AI) and Machine Learning (ML)
- Web Development
- Internet of Things (IoT) devices (e.g., Raspberry Pi)

Major organizations using Python include IBM, Google, NASA, Facebook, Amazon, and many more.

### Python as a Language

- Python is a high-level, general-purpose programming language.
- It has a large standard library supporting databases, automation, web scraping, text and image processing, machine learning, and data analytics.

### Python Libraries for Data Science & AI

- **Scientific Computing:** Pandas, NumPy, SciPy, Matplotlib
- **Artificial Intelligence & Machine Learning:** TensorFlow, PyTorch, Keras, Scikit-learn
- **Natural Language Processing (NLP):** Natural Language Toolkit (NLTK)

### Python Community & Diversity

- The Python community is supported by the Python Software Foundation.
- Python emphasizes diversity and inclusion in tech.
- The Python Code of Conduct promotes safety and inclusivity.
- Groups like PyLadies provide mentorship and foster safe spaces for women in Python.

### Python Data Types

Common Python data types include:

| Expression | Data Type | Description                  |
|------------|-----------|------------------------------|
| `11`       | `int`     | Integer (whole number)        |
| `21.213`   | `float`   | Floating point (real number)  |
| `"Hello"`  | `str`     | String (sequence of characters)|

- Integers can be positive or negative.
- Floats represent real numbers including decimals.
- Strings are sequences of characters.

### Typecasting

- Converting between data types is called typecasting.
- Examples:
  - Integer to float: `2` → `2.0`
  - Float to integer: `1.1` → `1` (may lose precision)
  - Strings containing numeric values can be converted to int or float.
  - Booleans (`True`/`False`) can convert to/from integers (`1`/`0`).

### Boolean Type

- Booleans represent logical values: `True` or `False`.
- Casting rules:
  - `True` → `1`, `False` → `0` (when cast to int or float)
  - `1` → `True`, `0` → `False` (when cast to bool)

### Expressions and Operations

- Python supports arithmetic operations: addition (+), subtraction (-), multiplication (*), division (/), and integer division (//).
- Operations follow mathematical precedence:
  - Parentheses first
  - Multiplication and division before addition and subtraction

Example:
```python
(32 + 0) * 60  # Result: 1920
```

---

## Compound Data Structures in Python

### Tuples
- Tuples are an **ordered sequence** enclosed in parentheses `()`.
- Elements can be of **different data types**: integers, floats, strings, etc.
- Each element can be accessed by an **index** (starting at `0`).
- Tuples are **immutable** (cannot be changed once created).
- Tuples can be **nested** (tuples inside tuples).
- Support **slicing** operations like lists.

Example:
```python
ratings = (10, 9, 8, "Great")
print(ratings[0])     # 10
print(ratings[-1])    # Great
print(ratings[0:3])   # (10, 9, 8)
```

---

### Lists
- Lists are an **ordered sequence** enclosed in square brackets `[]`.
- **Mutable**: elements can be added, changed, or removed.
- Can store different data types and support nesting.
- Support slicing and concatenation.

**Common methods:**
- `append()` → add one element  
- `extend()` → add multiple elements  
- `del` → remove an element  
- `split()` → convert strings to lists  

Example:
```python
L = ["Python", 3.7, 2023]
L.append("AI")
print(L)  # ["Python", 3.7, 2023, "AI"]
```

---

### Dictionaries
- A **collection of key-value pairs** enclosed in `{}`.
- Keys must be **unique** and **immutable** (e.g., strings, numbers).
- Values can be of any data type.
- Access values using their keys instead of indexes.

**Common methods:**
- `.keys()` → returns all keys  
- `.values()` → returns all values  

Example:
```python
album = {"Thriller": 1982, "Back in Black": 1980}
print(album["Thriller"])  # 1982
```

---

### Sets
- An **unordered collection** of unique elements enclosed in `{}`.
- Automatically removes duplicates.
- Support **mathematical set operations** like:
  - `union (|)`
  - `intersection (&)`
  - `issubset()`

Example:
```python
A = {"Python", "AI", "Data"}
B = {"AI", "ML"}

print(A & B)  # {"AI"}
print(A | B)  # {"Python", "AI", "Data", "ML"}
```
