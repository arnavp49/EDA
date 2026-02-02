
# Experiment 5: Sets and Dictionaries in Python
 Student Information
Name: Arnav Pandey

PRN: 25070123023

Topic: Study of Sets and Dictionaries




## Objectives
- Understand the properties of Sets (unordered, unindexed, no duplicates).

- Master Set operations like Union, Intersection, and Difference.

- Explore Dictionaries for key-value pair storage and retrieval.

- Implement data structures to solve logic-based programming problems.
## Theory: Sets and Dictionaries in Python
In Python, sets and dictionaries are powerful, built-in data structures used to store collections of data with specific properties.

1. Python Sets
A Set is an unordered collection of items where every element is unique (no duplicates) and must be immutable.

- Unordered: The items do not have a defined order; they may appear in a different order every time you use them and cannot be referred to by index or key.

- Duplicates Not Allowed: Sets automatically filter out duplicate values. For example, if you try to include "cat" twice, it will only appear once in the resulting set.

- Boolean Logic: In sets, the values True and 1 (as well as False and 0) are considered the same value and are treated as duplicates.

- Frozenset: This is an immutable version of a set. Once created, elements cannot be added or removed.

2. Python Dictionaries
- A Dictionary is a collection used to store data values in key:value pairs.

- Key-Value Structure: Data is retrieved by referencing a unique key rather than an index.

- Ordered (Python 3.7+): As of Python 3.7, dictionaries are ordered, meaning they maintain the order of insertion.

- No Duplicates: Dictionaries cannot have two items with the same key. If a duplicate key is provided, the latest value will overwrite the previous one.

- Versatility: They are ideal for representing real-world objects, such as a student profile (Name, Roll No, Branch) or a product catalog (Product Name, Price).
## Conclusion
This experiment successfully demonstrates the practical implementation of Sets and Dictionaries to solve data-driven problems.

- Sets were found to be highly efficient for tasks involving membership testing, removing duplicate entries from lists, and performing mathematical operations like finding common subjects (intersection) or identifying unique club members (symmetric difference).

- Dictionaries proved to be the superior choice for mapping related data, such as student marks, user credentials, or product pricing, allowing for quick retrieval and updates through unique keys.