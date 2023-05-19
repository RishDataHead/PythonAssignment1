# Q1. Why do we call Python as a general purpose and high-level programming language?


Python is considered a general-purpose language because it can be used for a wide range of applications.

It is called a high-level language because it abstracts away low-level details and provides a simplified syntax.

Python's syntax is readable and resembles natural language, making it easy to understand and maintain.

The language emphasizes code readability, simplicity, and conciseness.

Python has a vast ecosystem of libraries and frameworks, covering various domains, which extend its capabilities.

It is a cross-platform language, allowing programs to run on different operating systems without major modifications.

These characteristics make Python a popular choice for a diverse set of applications, making it a general-purpose and high-level programming language.

# Q2. Why is Python called a dynamically typed language?

Python does not require explicit type declarations for variables. For example x = 5 , x= "Hello"
The type of a variable is determined dynamically based on the value assigned to it.
Variables can hold values of different types during runtime.
Python uses type inference to determine the type of a variable based on its assigned value.


# Q3. List some pros and cons of Python programming language?

Pros:

Readability: Python has a clean and readable syntax, making it easier to write and understand code.
Large Standard Library: Python comes with a comprehensive standard library, providing a wide range of modules and functions that can be used for various tasks without the need for external dependencies.
Vast Ecosystem: Python has a rich ecosystem of third-party libraries and frameworks that cover a wide range of domains, enabling developers to leverage existing solutions and accelerate development.
Easy Integration: Python allows seamless integration with other languages such as C/C++, Java, and .NET, making it suitable for building large-scale applications that require different components.
Rapid Development: Python's simplicity and productivity-focused features, such as dynamic typing and automatic memory management, contribute to faster development cycles.
Cross-Platform Compatibility: Python is available on multiple platforms, allowing developers to write code once and deploy it on different operating systems.

Cons:

Performance: Python is an interpreted language, which can make it slower compared to compiled languages like C or C++. However, performance-critical sections of code can be optimized using compiled extensions or by utilizing specialized libraries.
Global Interpreter Lock (GIL): The GIL in CPython (the reference implementation of Python) can limit the execution of threads in parallel, which can impact the performance of CPU-bound multi-threaded applications. However, Python offers solutions such as multiprocessing and asynchronous programming to overcome this limitation.
Mobile Development: While Python can be used for mobile app development, it is not as widely adopted as languages like Java or Swift in the mobile development space.
Design Restrictions: Python's emphasis on readability and simplicity can lead to design restrictions and less control over low-level details compared to lower-level languages.
Version Compatibility: The transition from Python 2 to Python 3 introduced some backward-incompatible changes, resulting in a split between the two versions. This can lead to compatibility issues when working with legacy code or libraries.

# Q4. In what all domains can we use Python?

Python can be used in various domains, including:

Web development
Data analysis and visualization
Scientific computing
Machine learning and artificial intelligence
Automation and scripting
Game development
Network programming and cybersecurity
DevOps and system administration
Natural language processing
Robotics

# Q5. What are variable and how can we declare them?

A variable is a named storage location in a programming language that holds a value. It allows us to store and manipulate data during the execution of a program. In Python, variables can be declared and assigned values using the following syntax:

x = 5 
 
Declares a variable x with a value of 5 assigned to it

# Q6. How can we take an input from the user in Python?

#Input can be taken by using the input function in python.

x = input("give input")

#any contrainst of variable type can also be applied here for example int(input) or float(input) etc

# Q7. What is the default datatype of the value that has been taken as an input using input() function?

The default datatype is String

# Q8. What is type casting?

Typecasting in Python refers to the process of converting the data type of a variable from one type to another. It allows you to change the interpretation or representation of the data.

For example, you can convert an integer to a floating-point number, a string to an integer, or vice versa. Python provides built-in functions for typecasting, such as int(), float(), str(), bool(), and more.

Typecasting is useful when you need to perform operations that require compatible data types or when you want to manipulate and represent data in a different format.

# Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

No, the built-in input() function in Python allows you to take only a single input from the user at a time. It reads the input as a string until the user presses the Enter key.

# Q10. What are keywords?

Keywords, also known as reserved words, are predefined words in a programming language that have special meanings and purposes. These words are reserved and cannot be used as identifiers (variable names, function names, etc.) because they are already assigned a specific meaning and functionality by the language itself.

In Python, keywords are used to define the syntax and structure of the language and represent fundamental building blocks. They are used to declare control structures, define functions, handle exceptions, and perform other essential operations.

Here are some examples of Python keywords:

if, else, elif: Used for conditional statements
for, while: Used for loop iterations
def: Used to define functions
try, except, finally: Used for exception handling
import, from, as: Used for importing modules and packages
return: Used to specify the return value of a function
class: Used to define classes
and, or, not: Used for logical operations
True, False, None: Used for boolean and null values
Python provides a fixed set of keywords, and their usage is predefined by the language. It's important to avoid using keywords as identifiers in your code to prevent conflicts and syntax errors.

# Q11. Can we use keywords as a variable? Support your answer with reason.

No, keywords cannot be used as variables in Python. Keywords are reserved by the language and have predefined meanings and functionality. They serve as building blocks and control structures in Python syntax.

Attempting to use a keyword as a variable will result in a syntax error because the language expects certain behavior or functionality associated with keywords, and using them as variables would violate this expectation.

# Q12. What is indentation? What's the use of indentation in Python?

Indentation refers to the whitespace (spaces or tabs) placed at the beginning of a line of code to indicate its level of indentation within a block or scope. In Python, indentation is not merely a matter of style; it is a fundamental aspect of the language's syntax and structure.
The use of indentation in Python serves two main purposes:

Code Block Delimiters: Indentation is used to define the beginning and end of code blocks, such as loops, conditional statements, and function definitions. It specifies the group of statements that belong together and should be executed as a unit. Blocks of code at the same level of indentation are considered part of the same block.

Readability and Structure: Indentation improves the readability and structure of the code. By enforcing consistent and meaningful indentation, Python promotes code that is easier to understand, follow, and debug. Indentation helps in visualizing the hierarchical structure of the code and enhances code readability, especially for nested blocks.

# Q13. How can we throw some output in Python?

We can get output in python by using the Print keyword.

For example : Print("hello world") will give output as
hello world

# Q14. What are operators in Python?

In Python, operators are special symbols or characters that represent specific operations to manipulate or operate on operands (variables, values, or expressions). Operators allow you to perform various computations, comparisons, assignments, and logical operations in your code.

Here are the main types of operators in Python:

Arithmetic Operators: Perform mathematical calculations.

Addition: +
Subtraction: -
Multiplication: *
Division: /
Floor Division: //
Modulo: %
Exponentiation: **
Comparison Operators: Compare the values of operands.

Equal to: ==
Not equal to: !=
Greater than: >
Less than: <
Greater than or equal to: >=
Less than or equal to: <=
Assignment Operators: Assign values to variables.

Assignment: =
Addition assignment: +=
Subtraction assignment: -=
Multiplication assignment: *=
Division assignment: /=
Modulo assignment: %=
Exponentiation assignment: **=
Floor division assignment: //=
Logical Operators: Perform logical operations on boolean values.

Logical AND: and
Logical OR: or
Logical NOT: not
Bitwise Operators: Perform operations on binary representations of integers.

Bitwise AND: &
Bitwise OR: |
Bitwise XOR: ^
Bitwise NOT: ~
Left shift: <<
Right shift: >>
Membership Operators: Check for membership in a sequence.

in: Returns True if a value is found in a sequence.
not in: Returns True if a value is not found in a sequence.
Identity Operators: Compare the identity of objects.

is: Returns True if two objects have the same identity.
is not: Returns True if two objects have different identities.
These are some of the commonly used operators in Python. Understanding and utilizing operators allows you to perform a wide range of operations and computations in your programs.

# Q15. What is difference between / and // operators?# 

/ performs normal division and always returns a floating-point result.
// performs floor division and returns an integer result if both operands are integers.
The // operator disregards the decimal part and rounds down to the nearest integer.
It's important to consider the desired outcome and the data types of the operands when choosing between / and // for division operations in Python.

# Q16. Write a code that gives following as an output.
iNeuroniNeuroniNeuroniNeuron

print("iNeuroniNeuroniNeuroniNeuron")

# Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

num = int(input("Give number to check"))
if num%2 == 0:
    print("Even number")
else:
    print("Odd numer")

# Q18. What are boolean operator?

    Boolean operators in Python are used to perform logical operations on Boolean values (True or False) or expressions. Python provides three main Boolean operators:

Logical AND (and): Returns True if both operands are True, otherwise False.

Example: True and True returns True, True and False returns False.
Logical OR (or): Returns True if at least one of the operands is True, otherwise False.

Example: True or False returns True, False or False returns False.
Logical NOT (not): Returns the opposite of the operand's Boolean value. If the operand is True, not returns False. If the operand is False, not returns True.

Example: not True returns False, not False returns True.
These Boolean operators can be used to combine and evaluate Boolean expressions, control the flow of conditional statements, and perform logical operations in Python programs.

Additionally, Python also allows the use of bitwise operators (&, |, ^, ~) that can operate on the binary representations of integers but can also be used as boolean operators when applied to boolean values or expressions. However, their behavior is slightly different from the logical operators mentioned above.

# Q19. What will the output of the following?
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

1 or 0


0 and 0

True and False and True

1 or 0 or 0

# Q20. What are conditional statements in Python?

Conditional statements in Python are control structures that allow you to execute different blocks of code based on certain conditions. They help in controlling the flow of the program by making decisions based on the truth or falsehood of specific expressions. The main conditional statements in Python are:

if statement: Executes a block of code if a condition is true.
else statement: Provides an alternative block of code to execute if the preceding if condition is false.
elif statement: Allows you to specify additional conditions to check if the preceding if condition is false.

# Q21. What is use of 'if', 'elif' and 'else' keywords?

if statement: Executes a block of code if a condition is true.
else statement: Provides an alternative block of code to execute if the preceding if condition is false.
elif statement: Allows you to specify additional conditions to check if the preceding if condition is false.

# Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age = int(input("Enter age to check"))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")

# Q23. Write a code that displays the sum of all the even numbers from the given list.

list1 = [12, 75, 150, 180, 145, 525, 50]
sum = 0

for i in range(0,len(list1)):
    if list1[i]%2==0:
        sum = sum + list1[i]
    else:
        pass
   
print(sum)
    

# Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num1 = int(input("Give number 1 "))
num2 = int(input("Give number 2 "))
num3 = int(input("Give number 3 "))

if (num1 >= num2) and (num1 >= num3):
    largest = num1
elif (num2 >= num1) and (num2 >= num3):
    largest = num2
else:
    largest = num3
print(largest)

# Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]

numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if i%5 ==0:
        print(i)

numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if i>150:
        continue
    else:
        print(i)

numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if i >500:
        break
    else:
        print(i)

