# BIC502A — Unit III Practice Test

## Python Data Structures, Control Flow and Functions

**Instructions:** Answer all 15 questions. Write Python code wherever required.

---

## Section A — Basic

### 1. Variables and Data Types

Create four variables to store:
- A gene name
- A DNA sequence
- The length of the sequence
- Whether the sequence is coding or non-coding (`True/False`)

Also write the data type of each variable.

---

### 2. Strings

Given:

```python
dna = "ATGCGTACG"
```

Write Python statements to find:
- The length of the sequence
- The number of `G` bases
- The number of `A` bases

---

### 3. Indexing

For the sequence:

```python
dna = "ATGCGTACG"
```

What will be the output of:

```python
print(dna[0])
print(dna[4])
print(dna[-1])
print(dna[-3])
```

---

### 4. Slicing

Using:

```python
dna = "ATGCGTACG"
```

Write Python statements to extract:

a) The first three bases  
b) Bases from position 3 to 6  
c) The last three bases  
d) The reverse sequence

---

## Section B — Data Structures and Conditions

### 5. Lists

Create a list containing the following genes:

```text
TP53, BRCA1, EGFR, KRAS, MYC
```

Write Python statements to:
- Add `BRAF`
- Remove `EGFR`
- Print the first gene
- Print the total number of genes

---

### 6. Dictionary

Create a dictionary containing the following information about a gene:

```text
Name: TP53
Length: 393
Organism: Human
Chromosome: 17
```

Write Python code to print the gene name and chromosome.

---

### 7. List vs Tuple vs Set vs Dictionary

Briefly explain the main purpose of each:

```text
List
Tuple
Set
Dictionary
```

Give **one biological example** for each.

---

### 8. Conditional Statement

Write a Python program that checks the length of a DNA sequence.

The program should print:

```text
Short sequence
```

if the length is less than 50, and

```text
Long sequence
```

if the length is 50 or more.

---

### 9. Multiple Conditions

Given:

```python
gc = 65
length = 120
```

Write an `if` statement that prints:

```text
Suitable sequence
```

only when **GC content is greater than 50 AND sequence length is greater than 100**.

---

## Section C — Loops

### 10. For Loop

Given:

```python
dna = "ATGCGTACG"
```

Write a `for` loop to print each nucleotide on a separate line.

---

### 11. Counting Using a Loop

Write a Python program using a `for` loop to count the number of `G` bases in:

```python
dna = "ATGCGGATGCG"
```

---

### 12. `break` and `continue`

Explain the difference between `break` and `continue`.

Then write a short example of each using a loop.

---

## Section D — Functions

### 13. Function for Sequence Length

Write a function called `sequence_length()` that accepts a DNA sequence as input and returns its length.

Test it using:

```python
"ATGCGTACG"
```

---

### 14. Function for GC Content

Write a function called `gc_content()` that calculates and returns the GC percentage of a DNA sequence.

Use:

```python
dna = "ATGCGC"
```

The formula is:

```text
GC% = (G + C count / sequence length) × 100
```

---

## Section E — Moderate / Integrated

### 15. Bioinformatics Mini-Program

Consider the following sequences:

```python
sequences = {
    "Gene_A": "ATGCGTACG",
    "Gene_B": "GGCCGCGC",
    "Gene_C": "ATATATAT"
}
```

Write a Python program that uses a **function and a loop** to print the following for every gene:

```text
Gene: Gene_A
Length: ...
GC Content: ... %
```

Your program should work automatically for all three genes without writing separate code for each gene.
