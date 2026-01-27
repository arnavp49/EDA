
# Experiment 3: Mastering Python Lists
## Aim
To understand and implement Python tuples by exploring their properties of indexing and immutability, verifying memory address changes during operations, and applying tuple logic to solve real-world data tracking problems.
## Theory
Tuples are a built-in Python data type used to store multiple items in a single variable. They are characterized by the following properties:

- Ordered: The items have a defined order, and that order will not change.

- Immutable: Once a tuple is created, you cannot change, add, or remove items.

- Allow Duplicates: Since tuples are indexed, they can have items with the same value.

- Memory Management: Because they are immutable, modifying a tuple (e.g., using +=) actually creates a new object in memory with a different unique ID.
- Methods: Tuples have limited built-in methods, such as .count(), which is used to find the frequency of a specific element within the sequence.
## Implementation Details
1. Fundamental Operations
- Accessing Items: Demonstrates how to retrieve elements using index values.

- Immutability Test: A code block specifically designed to show that tuple object does not support item assignment.

- Address Verification: Uses the id() function to show the memory location change before and after a tuple concatenation.

2. Practical Applications
- Attendance Tracker: Stores "P" and "A" values in a tuple, calculates totals for each, and checks if an "Absent" record exists.

- Exam Result System: Manages subject-specific data (name, marks, and grade) and uses conditional logic to identify and print "Distinction" status for scores above 75.
## Conclusion
The experiment validates that tuples are an effective choice for data that should remain constant throughout a program's execution. Through practical exercises, it was observed that while tuples are immutable, they can be used dynamically to perform counts and conditional checks for record-keeping systems. The memory ID verification further reinforces the understanding of how Python handles immutable objects under the hood.

