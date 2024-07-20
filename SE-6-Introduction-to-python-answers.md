# SE-Assignment-6
Assignment: Introduction to Python

Questions:

> # 1. Python Basics:
> What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high-level, interpreted programming language known for its simplicity and readability. Created by Guido van Rossum and first released in 1991, it emphasizes code readability with its clear syntax and indentation. Here are some key features that make Python popular among developers:

### Key Features:

1. **Readability and Simplicity**: Python’s syntax is designed to be intuitive and its code is easy to read and write. This helps developers to write clear, logical code for both small and large projects.

2. **Interpreted Language**: Python code is executed line by line, which makes debugging easier and allows for interactive coding.

3. **Dynamic Typing**: Python does not require explicit declarations of variable types, which allows for more flexible and faster development.

4. **Extensive Standard Library**: Python comes with a large standard library that supports many common programming tasks such as file I/O, system calls, and data manipulation.

5. **Versatility**: Python can be used for a wide range of applications, from web development to data analysis to automation.

6. **Cross-Platform Compatibility**: Python can run on various operating systems, including Windows, macOS, and Linux, which makes it highly portable.

7. **Community and Ecosystem**: Python has a large, active community and a wealth of third-party libraries and frameworks, which accelerates development and problem-solving.

8. **Object-Oriented and Functional Programming**: Python supports multiple programming paradigms, including object-oriented, procedural, and functional programming.

9. **Integration**: Python can easily integrate with other languages and technologies, such as C/C++, Java, and web technologies.

### Use Cases:

1. **Web Development**: Python is widely used in web development with frameworks like Django and Flask. It’s used to build web applications and services efficiently.

   **Example**: Django is a popular framework for building scalable web applications quickly, such as content management systems or e-commerce sites.

2. **Data Analysis and Visualization**: Python is a go-to language for data analysis and visualization due to libraries like Pandas, NumPy, and Matplotlib.

   **Example**: Data scientists use Python to analyse large datasets and generate visual reports or perform complex statistical analyses.

3. **Machine Learning and Artificial Intelligence**: Libraries such as TensorFlow, Keras, and scikit-learn make Python a top choice for developing machine learning and AI models.

   **Example**: Python is used to build predictive models for financial forecasting, image recognition, and natural language processing.

4. **Automation and Scripting**: Python’s simplicity makes it an excellent choice for writing scripts to automate repetitive tasks.

   **Example**: Automation scripts can be used to process files, automate web interactions, or manage system configurations.

5. **Scientific Computing**: Python is used in scientific computing for simulations and complex mathematical computations, thanks to libraries like SciPy and SymPy.

   **Example**: Researchers use Python to model physical systems or analyze experimental data.

6. **Game Development**: Python can be used for game development with libraries such as Pygame, which allows for the creation of 2D games and prototyping.

   **Example**: Simple 2D games and educational games are often developed with Pygame.

7. **Networking**: Python's libraries can be used to build network applications and handle protocols.

   **Example**: Python can be used to create network tools for monitoring or managing network traffic.

These features and use cases illustrate why Python is a popular choice for many developers and industries, offering flexibility and efficiency across a broad spectrum of applications.

># 2. Installing Python:
>Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

Python is a general-purpose language which is designed to be used in a range of applications. It is often used to build websites/software, automate tasks and conduct data analysis.

Setting up Python Involves the following steps.

1.	First visit the official Python Website and download the latest version of python for Windows. Be sure to choose the installer for your Version of Windows (32 bit or 64 bit)
2.	Go to your downloads. Open and run the Python installer. 
3.	Select the default python installer.
4.	Set the path manually on your machine by opening the ‘Edit the System Environment Variables’ application on your computer.
5.	Go to Environment variables. 
6.	Click on 'Path' and select edit.
7.	Select 'New' and paste the path to your Python installation folder.
8.	Click ok to save the changes.
9.	Verify that python was installed by opening the cmd application on your computer and running it as an administrator. Type the command:

python –version

### Set Up a Virtual Environment:
1.	Open Terminal.
2.	Navigate to your project directory by typing in the command 

    cd path/to/your/project

3.	Create a virtual environment

    python3 -m venv myenv

4.	Activate the virtual environment

    source venv/bin/activate


># 3. Python Syntax and Semantics:
  >Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
## Simple Hello World program in Python

print("Hello, World!")

```python
# Simple Hello World program in Python

# Print the string "Hello, World!" to the console
print("Hello, World!")
```

### Explanation of Basic Syntax Elements:

1. **Comments (`#`)**:
   - Comments in Python start with the `#` symbol and are used to annotate code. They are ignored by the Python interpreter and are meant for human readers to understand the code better.

2. **Function Call (`print("Hello, World!")`)**:
   - `print()` is a built-in Python function that outputs (prints) the given message or variable to the console. In this case, `"Hello, World!"` is the string passed as an argument to `print()`.

3. **String (`"Hello, World!"`)**:
   - `"Hello, World!"` is a string literal enclosed in double quotes (`"`). In Python, strings are sequences of characters, and they can be enclosed in either single quotes (`'`) or double quotes (`"`).

### Program Flow:
- When you run this Python script, the interpreter executes each line sequentially.
- It encounters the `print("Hello, World!")` statement, which instructs it to output `"Hello, World!"` to the console.

This is a very basic Python program that demonstrates how to print a message to the console.

># 4. Data Types and Variables:
  > List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

### Basic Data Types in Python

1. **Integer (`int`)**:
   - Whole numbers, positive or negative, without a decimal point.
   - Example: `42`, `-7`

2. **Floating Point (`float`)**:
   - Numbers with a decimal point.
   - Example: `3.14`, `-0.001`

3. **String (`str`)**:
   - Sequence of characters enclosed in single (`'`) or double (`"`) quotes.
   - Example: `"Hello, World!"`, `'Python'`

4. **Boolean (`bool`)**:
   - Represents one of two values: `True` or `False`.
   - Example: `True`, `False`

5. **List (`list`)**:
   - Ordered collection of items, which can be of different types, enclosed in square brackets.
   - Example: `[1, 2, 3]`, `['apple', 'banana', 'cherry']`

6. **Tuple (`tuple`)**:
   - Ordered collection of items, which can be of different types, enclosed in parentheses. Tuples are immutable.
   - Example: `(1, 2, 3)`, `('apple', 'banana', 'cherry')`

7. **Dictionary (`dict`)**:
   - Unordered collection of key-value pairs, enclosed in curly braces.
   - Example: `{'name': 'Alice', 'age': 25}`

8. **Set (`set`)**:
   - Unordered collection of unique items, enclosed in curly braces.
   - Example: `{1, 2, 3}`, `{'apple', 'banana', 'cherry'}`

## Script Demonstrating Different Data Types

```python
# Integer
my_int = 42
print("Integer:", my_int)

# Floating Point
my_float = 3.14
print("Float:", my_float)

# String
my_str = "Hello, World!"
print("String:", my_str)

# Boolean
my_bool = True
print("Boolean:", my_bool)

# List
my_list = [1, 2, 3, 4, 5]
print("List:", my_list)

# Tuple
my_tuple = (1, 2, 3, 4, 5)
print("Tuple:", my_tuple)

# Dictionary
my_dict = {'name': 'Alice', 'age': 25}
print("Dictionary:", my_dict)

# Set
my_set = {1, 2, 3, 4, 5}
print("Set:", my_set)

# Accessing elements
print("First element in list:", my_list[0])
print("Name from dictionary:", my_dict['name'])

# Modifying data
my_list.append(6)
print("Modified list:", my_list)
my_dict['age'] = 26
print("Modified dictionary:", my_dict)
```

### Explanation of the Script:

1. **Creating Variables**:
   - Each variable is assigned a value of a specific data type using the assignment operator (`=`).

2. **Printing Variables**:
   - `print()` function is used to output the values of the variables to the console.

3. **Accessing Elements**:
   - Lists and tuples: Access elements using square brackets with the index (starting from 0).
   - Dictionaries: Access values using square brackets with the key.

4. **Modifying Data**:
   - Lists: Use methods like `append()` to modify the list.
   - Dictionaries: Update values by assigning a new value to an existing key.

This script covers basic operations with different data types, including creation, access, and modification.

># 5. Control Structures:
>Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

### Conditional Statements in Python

Conditional statements allow you to execute certain blocks of code based on specific conditions. The most common conditional statements in Python are `if`, `elif`, and `else`.

## `if-else` Statement

The `if-else` statement checks a condition and executes a block of code if the condition is true. If the condition is false, it can optionally execute another block of code.

**Syntax:**
```python
if condition:
    # Block of code to execute if the condition is true
elif another_condition:
    # Block of code to execute if the another_condition is true
else:
    # Block of code to execute if none of the above conditions are true
```

**Example:**
```python
age = 18

if age < 18:
    print("You are a minor.")
elif age == 18:
    print("You are exactly 18 years old.")
else:
    print("You are an adult.")
```

## Loops in Python

Loops allow you to execute a block of code multiple times. Python has two main types of loops: `for` loops and `while` loops.

#### `for` Loop

The `for` loop iterates over a sequence (such as a list, tuple, string, or range) and executes a block of code for each item in the sequence.

**Syntax:**
```python
for item in sequence:
    # Block of code to execute for each item
```

**Example:**
```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

## Combined Example

Here's a combined example demonstrating both an `if-else` statement and a `for` loop:

```python
### List of ages
ages = [15, 18, 22, 17, 30]

### Loop through each age in the list
for age in ages:
    if age < 18:
        print(f"Age {age}: You are a minor.")
    elif age == 18:
        print(f"Age {age}: You are exactly 18 years old.")
    else:
        print(f"Age {age}: You are an adult.")
```

### Explanation:

1. **Conditional Statement (`if-else`):**
   - The `if` statement checks if the condition `age < 18` is true. If it is, it prints that the person is a minor.
   - The `elif` statement checks if the condition `age == 18` is true. If it is, it prints that the person is exactly 18 years old.
   - The `else` statement is executed if none of the above conditions are true, printing that the person is an adult.

2. **Loop (`for`):**
   - The `for` loop iterates over each item in the `ages` list.
   - For each `age` in the list, the code inside the loop (including the `if-else` statement) is executed.

This combined example demonstrates how to use conditional statements to make decisions based on different conditions and how to use loops to repeat actions for each item in a sequence.

># 6. Functions in Python:
>What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

## Functions in Python

Functions in Python are blocks of reusable code that perform a specific task. They help organize and manage code, making it more readable and maintainable. Functions can take inputs (arguments), perform operations, and return outputs (results).

#### Benefits of Using Functions:

1. **Modularity**: Break down complex problems into smaller, manageable pieces.
2. **Reusability**: Write code once and reuse it multiple times.
3. **Readability**: Make code more organized and easier to understand.
4. **Maintainability**: Simplify debugging and updates by isolating functionality.

### Defining a Function

Functions are defined using the `def` keyword, followed by the function name, parentheses with optional parameters, and a colon. The function body is indented and contains the code to execute.

**Syntax:**
```python
def function_name(parameters):
 # Function body
    return result
```

### Example: Function to Sum Two Numbers

Here’s a Python function that takes two arguments and returns their sum:

```python
def add_numbers(a, b):




    """
    This function takes two arguments and returns their sum.
    
    Parameters:
    a (int, float): The first number.
    b (int, float): The second number.
    
    Returns:
    int, float: The sum of the two numbers.
    """
    return a + b
```

### Calling the Function

To use the function, call it with the required arguments and store or print the result.

**Example:**

```python
# Calling the function with integers
result1 = add_numbers(5, 3)
print("The sum of 5 and 3 is:", result1)  # Output: The sum of 5 and 3 is: 8

# Calling the function with floats
result2 = add_numbers(4.5, 2.3)
print("The sum of 4.5 and 2.3 is:", result2)  # Output: The sum of 4.5 and 2.3 is: 6.8
```

### Explanation:

1. **Function Definition:**
   - The `def add_numbers(a, b):` line defines a function named `add_numbers` that takes two parameters, `a` and `b`.
   - The `"""` docstring `"""` provides a description of the function, including its parameters and return value.
   - The `return a + b` line returns the sum of the two parameters.

2. **Function Call:**
   - The function is called with two arguments, `5` and `3`, and the result is stored in the variable `result1`.
   - The result is printed to the console.
   - The function is called again with two float arguments, `4.5` and `2.3`, and the result is stored in the variable `result2`.
   - The result is printed to the console.

Functions are powerful tools in Python programming, enabling better code organization, reuse, and readability.

># 7. Lists and Dictionaries:
>Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
### Differences Between Lists and Dictionaries in Python

## **Lists:**
- **Ordered**: Elements have a defined order, and you can access elements using their index.
- **Mutable**: You can change elements (add, remove, or modify).
- **Indexed by Integers**: Access elements by their position (index) in the list.
- **Allows Duplicates**: Can contain duplicate elements.

## **Dictionaries:**
- **Unordered**: Elements have no defined order (as of Python 3.7, they are insertion-ordered, but conceptually unordered).
- **Mutable**: You can change elements (add, remove, or modify).
- **Indexed by Keys**: Access elements by keys, which can be of any immutable type (e.g., strings, numbers, tuples).
- **No Duplicates**: Keys must be unique, but values can be duplicated.

### Example Script

Here’s a script that creates a list of numbers and a dictionary with key-value pairs, demonstrating basic operations on both.

```python
# Create a list of numbers
numbers = [1, 2, 3, 4, 5]

# Create a dictionary with key-value pairs
person = {
    'name': 'Alice',
    'age': 30,
    'city': 'New York'
}

# Basic Operations on List
print("Original list:", numbers)

# Accessing elements by index
print("First element in the list:", numbers[0])

# Adding an element
numbers.append(6)
print("List after adding an element:", numbers)

# Removing an element

numbers.remove(3)
print("List after removing an element:", numbers)

# Modifying an element
numbers[1] = 10
print("List after modifying an element:", numbers)

# Basic Operations on Dictionary
print("\nOriginal dictionary:", person)

# Accessing elements by key
print("Name:", person['name'])

# Adding a key-value pair
person['email'] = 'alice@example.com'
print("Dictionary after adding a key-value pair:", person)

# Removing a key-value pair
del person['city']
print("Dictionary after removing a key-value pair:", person)

# Modifying a value
person['age'] = 31
print("Dictionary after modifying a value:", person)
```

### Explanation:

1. **List Operations:**
   - **Creation**: `numbers = [1, 2, 3, 4, 5]` creates a list with five elements.
   - **Accessing Elements**: `numbers[0]` accesses the first element (index 0).
   - **Adding an Element**: `numbers.append(6)` adds `6` to the end of the list.
   - **Removing an Element**: `numbers.remove(3)` removes the first occurrence of `3` from the list.
   - **Modifying an Element**: `numbers[1] = 10` changes the second element (index 1) to `10`.

2. **Dictionary Operations:**
   - **Creation**: `person = {'name': 'Alice', 'age': 30, 'city': 'New York'}` creates a dictionary with three key-value pairs.
   - **Accessing Elements**: `person['name']` accesses the value associated with the key `'name'`.
   - **Adding a Key-Value Pair**: `person['email'] = 'alice@example.com'` adds a new key-value pair to the dictionary.
   - **Removing a Key-Value Pair**: `del person['city']` removes the key `'city'` and its associated value.
   - **Modifying a Value**: `person['age'] = 31` changes the value associated with the key `'age'` to `31`.

This script demonstrates the basic usage and differences between lists and dictionaries in Python, showcasing how to create, access, modify, add, and remove elements.

> # 8. Exception Handling:
> What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
### Exception Handling in Python

Exception handling in Python is a mechanism to handle runtime errors, allowing a program to continue running or gracefully handle errors without crashing. It is done using `try`, `except`, `else`, and `finally` blocks.

-  **`try` block**: Contains the code that might raise an exception.
- **`except` block**: Contains the code that runs if an exception occurs in the `try` block.
- **`else` block**: Contains the code that runs if no exceptions occur in the `try` block (optional).
- **`finally` block**: Contains the code that runs no matter what, whether an exception occurs or not (optional).

### Example Script Using `try`, `except`, and `finally`

```python
def divide(a, b):
    try:
        result = a / b
    except ZeroDivisionError as e:
        print("Error: Division by zero is not allowed.")
        result = None
    except TypeError as e:
        print("Error: Unsupported types for division.")
        result = None
    else:
        print("Division successful.")
    finally:
        print("Execution of the 'finally' block.")
    
    return result

# Test cases
print("Test 1: Division by zero")
result1 = divide(10, 0)
print("Result:", result1)

print("\nTest 2: Division with incorrect types")
result2 = divide(10, 'a')
print("Result:", result2)

print("\nTest 3: Successful division")
result3 = divide(10, 2)
print("Result:", result3)
```

### Explanation

1. **Function Definition**:
   - `def divide(a, b):` defines a function named `divide` that takes two arguments `a` and `b`.

2. **Try Block**:
   - `try:` contains the code that might raise an exception. In this case, it attempts to divide `a` by `b`.

3. **Except Blocks**:
   - `except ZeroDivisionError as e:` catches a division by zero error and prints a message. It sets `result` to `None`.
   - `except TypeError as e:` catches a type error (e.g., if `b` is a string) and prints a message. It also sets `result` to `None`.

4. **Else Block**:
   - `else:` executes if no exceptions are raised in the `try` block. It prints a success message.

5. **Finally Block**:
   - `finally:` contains code that runs no matter what. It prints a message indicating the execution of the `finally` block.

6. **Function Return**:
   - `return result` returns the result of the division or `None` if an exception was caught.

7. **Test Cases**:
   - **Test 1**: `divide(10, 0)` tests division by zero, which raises a `ZeroDivisionError`.
   - **Test 2**: `divide(10, 'a')` tests division with incorrect types, which raises a `TypeError`.
   - **Test 3**: `divide(10, 2)` tests a successful division, which should not raise any exceptions.

### Output
```
Test 1: Division by zero
Error: Division by zero is not allowed.
Execution of the 'finally' block.
Result: None

Test 2: Division with incorrect types
Error: Unsupported types for division.
Execution of the 'finally' block.
Result: None

Test 3: Successful division
Division successful.
Execution of the 'finally' block.
Result: 5.0
```

This script demonstrates how to handle exceptions using `try`, `except`, and `finally` blocks, ensuring that the program can handle errors gracefully and execute necessary clean up code regardless of whether an exception occurs.

># 9. Modules and Packages:
 >Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
### Modules and Packages in Python

#### Modules
A module in Python is a file containing Python definitions and statements. It can define functions, classes, and variables, and can also include runnable code. Modules help organize code into manageable sections and promote code reuse.

#### Packages
A package is a way of organizing related modules into a directory hierarchy. A package typically contains multiple modules, and it often includes a special `__init__.py` file to initialize the package. Packages allow for a more structured and modular codebase, especially in larger projects.

### Importing and Using a Module

To use a module in your script, you need to import it using the `import` statement. You can import the entire module, specific functions or classes, or give the module an alias.

#### Example: Using the `math` Module

The `math` module provides access to mathematical functions and constants.

**Example Script:**

```python
# Importing the math module
import math

# Using the math module functions and constants
number = 9

# Calculate the square root
sqrt_result = math.sqrt(number)
print(f"The square root of {number} is {sqrt_result}")

# Calculate the sine of a number (in radians)
angle = math.pi / 2  # 90 degrees in radians
sin_result = math.sin(angle)
print(f"The sine of {angle} radians is {sin_result}")

# Calculate the factorial of a number
factorial_result = math.factorial(5)
print(f"The factorial of 5 is {factorial_result}")

# Using a math constant
pi_value = math.pi
print(f"The value of pi is {pi_value}")
```

### Explanation:

1. **Importing the Module**:
   - `import math` imports the entire `math` module, making all its functions and constants available.

2. **Using Module Functions**:
   - `math.sqrt(number)`: Computes the square root of `number`.
   - `math.sin(angle)`: Computes the sine of `angle` (angle in radians).
   - `math.factorial(5)`: Computes the factorial of `5`.

3. **Using Module Constants**:
   - `math.pi`: Provides the value of π (pi).

### Importing Specific Functions or Giving an Alias

You can also import specific functions or give the module an alias for convenience.

**Import Specific Functions:**

```python
# Import specific functions from the math module
from math import sqrt, sin, pi

# Using the imported functions and constant
number = 9
sqrt_result = sqrt(number)
print(f"The square root of {number} is {sqrt_result}")

angle = pi / 2  # 90 degrees in radians
sin_result = sin(angle)
print(f"The sine of {angle} radians is {sin_result}")
```

**Giving an Alias:**

```python
# Import the math module with an alias
import math as m

# Using the alias to access math module functions and constants
number = 9
sqrt_result = m.sqrt(number)
print(f"The square root of {number} is {sqrt_result}")

angle = m.pi / 2  # 90 degrees in radians
sin_result = m.sin(angle)
print(f"The sine of {angle} radians is {sin_result}")
```

### Summary

- **Modules**: Single Python files containing definitions and statements.
- **Packages**: Directories containing multiple modules, often with an `__init__.py` file.
- **Importing Modules**: Use `import` to bring modules into your script.
- **Using Module Functions and Constants**: Access functions and constants with dot notation (`module.function()`).
- **Import Specific Functions**: Use `from module import function` to import specific functions.
- **Module Alias**: Use `import module as alias` to give a module an alias for easier access.

# 10. File I/O:
How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

### Reading from and Writing to Files in Python

Python provides built-in functions to handle file operations. The `open()` function is used to open files in different modes, such as read (`'r'`), write (`'w'`), and append (`'a'`). After performing file operations, it's important to close the file using the `close()` method or using a `with` statement that automatically handles closing the file.

### Reading from a File

To read the content of a file and print it to the console:

```python
# Script to read content from a file and print it to the console
def read_file(file_path):
    try:
        with open(file_path, 'r') as file:
            content = file.read()
            print(content)
    except FileNotFoundError:
        print(f"The file {file_path} does not exist.")

# Example usage
read_file('example.txt')
```

### Writing to a File

To write a list of strings to a file:

```python
# Script to write a list of strings to a file
def write_to_file(file_path, lines):
    try:
        with open(file_path, 'w') as file:
            for line in lines:
                file.write(line + '\n')
        print(f"Content successfully written to {file_path}.")
    except IOError as e:
        print(f"An error occurred while writing to the file: {e}")

# Example usage
lines_to_write = ["First line", "Second line", "Third line"]
write_to_file('output.txt', lines_to_write)
```

### Explanation

1. **Reading from a File**:
   - The `open(file_path, 'r')` function opens the file in read mode (`'r'`).
   - `with` statement ensures that the file is properly closed after its suite finishes, even if an exception is raised.
   - `file.read()` reads the entire content of the file.
   - If the file is not found, `FileNotFoundError` is caught and a message is printed.

2. **Writing to a File**:
   - The `open(file_path, 'w')` function opens the file in write mode (`'w'`), creating the file if it does not exist or truncating it if it does.
   - `with` statement ensures that the file is properly closed after its suite finishes.
   - `file.write(line + '\n')` writes each string from the list to the file, adding a newline character at the end.
   - If an I/O error occurs, it is caught and an error message is printed.

These scripts demonstrate how to perform basic file I/O operations in Python, including reading from a file and writing to a file.

# REFERENCES
1.	AskAI, private communication, July 2024
2.	ChatGPT, private communication, July 2024
3.	A. D. Sole, "Visual Studio Code Distilled", Cremona, Italy, 2018


