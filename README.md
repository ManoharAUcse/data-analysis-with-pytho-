# data-analysis-with-pytho-
Python program to create a list, a dictionary, and a set. Perform basic operations like adding, removing, and modifying elements
# Create a list, a dictionary, and a set
my_list = [1, 2, 3]
my_dict = {'a': 1, 'b': 2, 'c': 3}
my_set = {1, 2, 3}

# --- List Operations ---
print("Original List:", my_list)

# Add element to the list
my_list.append(4)
print("List after appending 4:", my_list)

# Modify an element in the list
my_list[0] = 10
print("List after modifying the first element to 10:", my_list)

# Remove an element from the list
my_list.remove(2)
print("List after removing 2:", my_list)

# --- Dictionary Operations ---
print("\nOriginal Dictionary:", my_dict)

# Add a new key-value pair to the dictionary
my_dict['d'] = 4
print("Dictionary after adding {'d': 4}:", my_dict)

# Modify the value of an existing key
my_dict['a'] = 10
print("Dictionary after modifying 'a' to 10:", my_dict)

# Remove a key-value pair from the dictionary
del my_dict['b']
print("Dictionary after removing key 'b':", my_dict)

# --- Set Operations ---
print("\nOriginal Set:", my_set)

# Add an element to the set
my_set.add(4)
print("Set after adding 4:", my_set)

# Remove an element from the set
my_set.discard(2)
print("Set after removing 2:", my_set)

# Try adding a duplicate element (which won't be added in a set)
my_set.add(3)
print("Set after trying to add duplicate 3 (no change):", my_set)