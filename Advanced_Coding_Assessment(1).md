# Advanced Coding Assessment

## Topics Covered
- Variables
- Data Types
- Type Conversion
- Input and Output
- Strings
- String Indexing
- String Slicing
- Lists
- Tuples
- Sets
- Dictionaries
- Arrays / Nested Lists

## Instructions
- Answer all 10 questions.
- Write Python code wherever required.
- Focus on logic, correct use of data structures, and interpretation of the output.

---

## 1. Data Types and Type Conversion

Consider the following code:

```python
a = "25"
b = 10
c = 2.5
d = True
```

Write a Python program to:

- Convert `a` into an integer.
- Convert `b` into a float.
- Convert `c` into a string.
- Convert `d` into an integer.
- Calculate and display the result of `(a + b) * c`.

---

## 2. String Analysis

Given:

```python
sequence = "ATGCGATATCGATGCGAT"
```

Write a program to determine:

- The length of the sequence.
- The number of occurrences of `"ATG"`.
- The number of occurrences of `"CG"`.
- The sequence in uppercase.
- The sequence obtained by taking every second character.

---

## 3. String Indexing and Slicing

Given:

```python
protein = "MKWVTFISLLFLFSSAYS"
```

Using **only indexing and slicing**, write a program to extract:

- The first 5 amino acids.
- The last 5 amino acids.
- Every second amino acid.
- The sequence from position 5 to position 12.
- The sequence in reverse order.

---

## 4. List Manipulation

Consider:

```python
marks = [78, 92, 65, 88, 72, 95, 81]
```

Write a program to:

- Find the highest and lowest marks **without using `max()` or `min()`**.
- Calculate the average without using `sum()`.
- Create a new list containing only marks greater than 80.
- Replace the lowest mark with `70`.

---

## 5. Tuple and List

Consider:

```python
student = ("Riya", 21, "Biotechnology", 85, 92, 78)
```

Write a program to:

- Extract the student's name and course.
- Extract all three marks using slicing.
- Convert the marks into a list.
- Calculate the average mark.
- Determine whether the average is greater than 80.

---

## 6. Set Operations

Given:

```python
python_students = {"A", "B", "C", "D", "E"}
r_students = {"C", "D", "E", "F", "G"}
```

Using set operations, find:

1. Students who know **both Python and R**.
2. Students who know **either Python or R**.
3. Students who know Python but not R.
4. Students who know R but not Python.
5. Students who know neither Python nor R, assuming the complete student set is:

```python
{"A", "B", "C", "D", "E", "F", "G", "H"}
```

---

## 7. Dictionary Manipulation

Consider:

```python
student = {
    "name": "Rahul",
    "age": 22,
    "course": "Biotechnology",
    "marks": 85
}
```

Write a program to:

- Display the student's name and course.
- Change the marks to `91`.
- Add a new key `"grade"` based on the marks.
- Add a key `"passed"` whose value is `True` if marks are >= 50 and `False` otherwise.
- Display the updated dictionary.

---

## 8. Nested List Processing

Given:

```python
data = [
    [12, 5, 8],
    [7, 15, 3],
    [10, 6, 20]
]
```

Write a Python program to:

- Display the element `15`.
- Display the complete second row.
- Calculate the sum of each row.
- Find the largest value in the entire nested list **without using `max()`**.
- Create a new list containing all values greater than `10`.

---

## 9. Integrated Data Structure Problem

Consider:

```python
genes = {
    "Gene1": ["ATGCGT", "Human"],
    "Gene2": ["ATGAAA", "Mouse"],
    "Gene3": ["ATGCGC", "Human"],
    "Gene4": ["ATTTGC", "Rat"]
}
```

Write a program to:

- Display the sequence of `Gene3`.
- Find all genes belonging to `"Human"`.
- Calculate the length of every gene sequence.
- Create a new dictionary containing only the human genes.
- Display the final dictionary.

---

## 10. Comprehensive Nested Data Problem

A laboratory stores experimental data as follows:

```python
experiments = {
    "EXP01": {
        "sample": "A",
        "values": [12, 15, 18, 20]
    },
    "EXP02": {
        "sample": "B",
        "values": [8, 10, 7, 12]
    },
    "EXP03": {
        "sample": "C",
        "values": [22, 25, 19, 24]
    }
}
```

Write a Python program that:

- Extracts the values for each experiment.
- Calculates the average value for each experiment **without using `sum()`**.
- Identifies experiments whose average is greater than `15`.
- Stores the qualifying experiments in a new dictionary.
- Displays the experiment ID, sample name, and average value for each qualifying experiment.

### Skills Tested

This question requires you to combine:

- Dictionaries
- Nested dictionaries
- Lists
- Loops
- Indexing
- Variables
- Arithmetic operations
- Conditional statements
