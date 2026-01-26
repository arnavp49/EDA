
# Experiment 3: Mastering Python Lists
This repository contains an exploration of Python Lists, covering fundamental operations, built-in methods, and real-world application scenarios.



## Aim
To understand the properties of Python lists and perform various operations such as indexing, slicing, and manipulation using built-in functions.
## Theory
A List is one of the most versatile data types in Python. It is used to store multiple items in a single variable.

Key Features of Lists:
Ordered: Items have a defined order that will not change.

Changeable (Mutable): We can change, add, and remove items after the list has been created.

Allow Duplicates: Since lists are indexed, items can have the same value.

Heterogeneous: A single list can contain different data types (Strings, Integers, Booleans).
## Core Operations
1. Basic Manipulation
Initialization: Creating a list using square brackets [].

Length: Using len() to find the number of elements.

Accessing Items: Using positive indexing (starting from 0) and negative indexing (starting from -1).

Changing Values: Modifying specific elements by referring to their index number.

2. Adding & Extending
.append(): Adds an item to the end of the list.

.extend(): Adds multiple items (another list) to the end.

.insert(): Adds an item at a specific index.

3. Slicing
Slicing allows you to extract a specific range of items.

list[start:stop]

list[start:stop:step]
## Practical Case Studies Included
The notebook demonstrates real-world use cases for lists:

- Student Marks Management
Functions used: max(), min(), and .sort().

Calculate the highest and lowest scores.

Sort marks in ascending and descending (reverse) order.

- Grocery Shopping List
Functions used: .append() and .remove().

Dynamically adding items to a list.

Removing items after purchase or change of mind.

- Contact List Management
Functions used: .append() and .sort().

Storing names in a list and automatically alphabetizing them for easier access.

- Temperature Analysis
Functions used: sum() and len().

Performing statistical analysis such as finding the average temperature over a period.
## Conclusion
Python lists are a fundamental tool for any programmer. Their ability to grow dynamically and store diverse data types makes them ideal for tasks ranging from simple data storage to complex data analysis. This experiment successfully demonstrates how to manage, sort, and analyze data efficiently using list methods.