```python
#1 explain the key features of Python that make it a popular choice for programming.
```
1- Python is a programming language that is easy to understand and write, making it a popular choice among developers and programmers. 
2- It is compatible with various programming paradigms, such as procedural, object-oriented, and functional programming. 
3- Python has a large and active community of developers, an extensive standard library, and third-party packages for various domains.
4- Python is an interpreted language, meaning that code is executed line-by-line. This feature supports rapid prototyping and iterative development.
5- Python provides an interactive mode (REPL) that allows developers to test code snippets quickly and explore Python’s features interactively.
6- Its versatility makes it suitable for many different types of projects.
7- Python is used in a wide range of applications, from web development and data analysis to artificial intelligence and scientific computing. 
8- Python runs on various operating systems, including Windows, macOS, and Linux.
9- Python uses dynamic typing, which means you don’t need to declare variable types explicitly.
10- Python runs on various operating systems, including Windows, macOS, and Linux.

```python
#2 Describe the role of predefined keywords in Python and provide examples of how they are used in a program.
```
Predefined keywords are reserved words that have special meanings and purposes in the language. They are integral to Python’s syntax and structure, defining the fundamental constructs of the language. You cannot use these keywords as identifiers (e.g., variable names, function names) in your programs. Keywords are case-sensitive and cannot be redefined or overridden within a Python program.

Roles of Predefined Keywords:-
1- Control Flow: Keywords like if, elif, else, for, while, and break control the flow of execution in a program, allowing for conditional statements and loops.
2- Definition and Declaration: Keywords such as def and class are used to define functions and classes, respectively, establishing new code structures.
3- Data Types and Structures: Keywords like True, False, None, and import are used to represent special values and manage module imports.

Examples of How They Are Used:-
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is 5 or less")

```python
# 3 Compare and contrast mutable and immutable objects in Python with examples.
```
Mutable objects - can be changed after they are created. This means that their content or state can be modified without creating a new object. E.g., List and Dictionary

Immutable objects - cannot be changed once they are created. Any modification creates a new object rather than altering the existing one.
E.g., Tuple and String

Comparison-
1-
Mutable: Can be changed after creation (e.g., lists, dictionaries).
Immutable: Cannot be changed after creation (e.g., tuples, strings).
2-
Mutable: Useful when you need to change the content of an object over time.
Immutable: Useful when you need objects to remain constant and unchanged, providing a guarantee that the object won’t be modified elsewhere in the code.
3-
Mutable: Generally not hashable (e.g., lists, dictionaries), meaning they can’t be used as keys in dictionaries or elements in sets.
Immutable: Generally hashable (e.g., strings, tuples) and can be used as keys in dictionaries or elements in sets.

```python
# 4 Discuss the different types of operators in Python and provide examples of how they are used.
```
Python supports various types of operators, including arithmetic operators (+, -, *, /), comparison operators (==, !=, <, >), logical operators (and, or, not), assignment operators (=, +=, -=, *=, /=), etc.
Operators have precedence and associativity rules that determine the order of evaluation in expressions.

```python
# 5 Explain the concept of type casting in Python with examples.
```
Type casting in Python is the process of converting a variable from one data type to another. This is useful when you need to ensure that operations are performed on compatible types or when you want to format data in a specific way. Python provides built-in functions for type casting, such as int(), float(), str(), list(), tuple(), dict(), etc.
E.g.,
x = 5.7
y = int(x)
print(y)  # Output: 5

```python
# 6 How do conditional statements work in Python? Illustrate with examples.
```
Conditional statements in Python control the flow of execution based on whether certain conditions are true or false. They allow your program to make decisions and execute different code blocks depending on the outcome of those decisions.

E.g.,
score = 85

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
else:
    print("Grade: D")


```python
# 7 Describe the different types of loops in Python and their use cases with examples.
```
Loops are used to execute a block of code repeatedly based on certain conditions. There are two primary types of loops: for loops and while loops.
“for” loops are used for iterating over a sequence of elements, while “while” loops are used for executing code until a specified condition becomes False.

Use Cases of For loop:

Iterating over elements of a collection (e.g., list, tuple).
Generating a sequence of numbers using the range() function.
Performing operations on each item in a collection.

E.g., 
word = "hello"
for letter in word:
    print(letter)

Use Cases of while loop:

When the number of iterations is not known beforehand.
Continuously checking a condition or status until it changes.
Implementing infinite loops with a termination condition.

E.g.,
count = 0
while count < 5:
    print(count)
    count += 1
else:
    print("Loop finished.")