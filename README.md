[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15305981&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   
Python is a high-level, interpreted programming language known for its simplicity and readability. Key features include:

- Easy to Learn and Use: Simple syntax and readability.
- Interpreted: No compilation needed before execution.
- Cross-platform: Runs on Windows, macOS, Linux, etc.
- Large Standard Library: Extensive built-in modules for various tasks.
- Dynamically Typed: Variables don't need explicit declaration.
- Object-Oriented: Supports object-oriented programming paradigms.
- Extensible: Supports integration with other languages.

Use cases:
- Web Development: Frameworks like Django and Flask.
- Data Science and Machine Learning: Libraries like NumPy, Pandas, and TensorFlow.
- Automation and Scripting: Automating repetitive tasks.
- Prototyping: Quickly developing and testing ideas.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Installation steps vary slightly by operating system:

- Windows: Download installer from python.org, run it, and select "Add Python to PATH" during installation.
- macOS: Use Homebrew (`brew install python3`) or download installer from python.org.
- Linux: Use package manager (`sudo apt-get install python3` for Debian/Ubuntu).

Verify installation:
- Open terminal/command prompt and type `python --version` or `python3 --version`.

Setting up a virtual environment:
- Install `virtualenv` using `pip install virtualenv`.
- Create a virtual environment: `virtualenv myenv`.
- Activate virtual environment:
  - Windows: `myenv\Scripts\activate`
  - macOS/Linux: `source myenv/bin/activate`


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   
python
// Hello, World! program
print("Hello, World!")


Explanation:
- print(): Function to output text to the console.
- "Hello, World!": String literal enclosed in double quotes.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic data types:
- int: Integer numbers (`1, 2, 3`)
- float: Floating-point numbers (`1.0, 2.5, 3.14`)
- str: Strings (`"hello", 'world'`)
- bool: Boolean values (`True, False`)

Script example:
python
// Variable examples
my_int = 10
my_float = 3.14
my_str = "Hello, Python!"
my_bool = True

// Printing variables
print(my_int)
print(my_float)
print(my_str)
print(my_bool)



5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   
Conditional statement (`if-else`):
python
// if-else example
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is less than or equal to 5")


Loop (`for` loop):
python
// for loop example
for i in range(5):
    print(i)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.


   
Functions are reusable blocks of code that perform a specific task. They enhance code readability, maintainability, and reusability.

Example:
python
// Function to add two numbers
def add_numbers(a, b):
    return a + b

// Calling the function
result = add_numbers(3, 5)
print("Sum:", result)  // Output: Sum: 8



7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.


   
Lists:
- Ordered collection of elements.
- Accessed by index.
- Mutable (`append()`, `pop()`, etc.).

Dictionary:
- Unordered collection of key-value pairs.
- Accessed by key.
- Mutable (`update()`, `pop()`, etc.).

Script example:
python
// List example
my_list = [1, 2, 3, 4, 5]
print(my_list[0])  // Accessing element by index

// Dictionary example
my_dict = {'name': 'Alice', 'age': 30, 'city': 'New York'}
print(my_dict['age'])  // Accessing value by key



8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   
Exception handling manages and responds to errors that occur during execution.

Example:
python
// Exception handling example
try:
    x = 1 / 0  // Division by zero error
except ZeroDivisionError as e:
    print("Error:", e)
finally:
    print("Cleanup code or final statements")



9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules are Python files containing definitions and statements. Packages are directories of modules.

Example:
python
// Importing and using math module
import math

radius = 5
area = math.pi * radius  2
print("Area of circle:", area)


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.



Reading from a file:
python
// Reading from a file
with open('myfile.txt', 'r') as f:
    content = f.read()
    print(content)


Writing to a file:
python
// Writing to a file
data = ['apple', 'banana', 'cherry']
with open('fruits.txt', 'w') as f:
    for item in data:
        f.write(item + '\n')



// Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


