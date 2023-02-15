Python List and Dictionary Comprehension Techniques
List and dictionary comprehension are powerful features in Python that allow us to create new lists and dictionaries using a compact and readable syntax.
List Comprehension:
List comprehension provides a concise way to create lists. It consists of brackets containing an expression followed by a for clause, then zero or more for or if clauses. Here is an example of creating a list of squares:
# Create a list of squares from 0 to 9
squares = [x**2 for x in range(10)]
print(squares)
Output:
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
In the above code, we are using the range() function to generate numbers from 0 to 9. The list comprehension then takes each number, squares it using the expression x**2, and creates a new list.
We can also use an if clause to filter the list. Here is an example of creating a list of even numbers:
# Create a list of even numbers from 0 to 9
evens = [x for x in range(10) if x % 2 == 0]
print(evens)
Output:
[0, 2, 4, 6, 8]
In the above code, we are using an if clause to filter the list by checking if the number is even using the expression x % 2 == 0.
Dictionary Comprehension:
Dictionary comprehension is similar to a list comprehension, but it creates a new dictionary instead of a new list. It consists of curly braces containing a key-value pair followed by a for clause, then zero or more for or if clauses. Here is an example of creating a dictionary of squares:
# Create a dictionary of squares from 0 to 9
squares_dict = {x: x**2 for x in range(10)}
print(squares_dict)
Output:
{0: 0, 1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64, 9: 81}

In the above code, we are using the same expression as in the list comprehension, but this time we are assigning it to a key-value pair using the syntax x: x**2. This creates a new dictionary with keys from 0 to 9 and values as their squares.
We can also use an if clause to filter the dictionary. Here is an example of creating a dictionary of even numbers:
# Create a dictionary of even numbers from 0 to 9
evens_dict = {x: x for x in range(10) if x % 2 == 0}
print(evens_dict)
Output:
{0: 0, 2: 2, 4: 4, 6: 6, 8: 8}
In the above code, we are using an if clause to filter the dictionary by checking if the key is even using the expression x % 2 == 0.
List and dictionary comprehension can be a powerful tool in creating new data structures in Python, making code more concise and easier to read.
follow the below link for more examples of list and dictionary comprehension :
