# Python List Operations Program

## Description

This Python program demonstrates various list operations, including:
- Creating an empty list
- Appending elements to the list
- Inserting an element at a specific position
- Extending the list with another list
- Removing the last element
- Sorting the list in ascending order
- Finding the index of a specific element

## Features

- User-friendly and simple to understand
- Uses built-in Python list methods
- Outputs the list at each stage for clarity

## Code Example

```python
# Step 1: Create an empty list
my_list = []
print("Initial empty list:", my_list)

# Step 2: Append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print("After appending 10, 20, 30, 40:", my_list)

# Step 3: Insert 15 at the second position (index 1)
my_list.insert(1, 15)
print("After inserting 15 at index 1:", my_list)

# Step 4: Extend my_list with another list [50, 60, 70]
my_list.extend([50, 60, 70])
print("After extending with [50, 60, 70]:", my_list)

# Step 5: Remove the last element
my_list.pop()
print("After removing the last element:", my_list)

# Step 6: Sort my_list in ascending order
my_list.sort()
print("After sorting in ascending order:", my_list)

# Step 7: Find and print the index of value 30
index_30 = my_list.index(30)
print("Index of value 30:", index_30)
