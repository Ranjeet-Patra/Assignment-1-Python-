## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans: General-purpose: Python is a general-purpose programming language, which means it can be used to build a wide variety of applications. It can be used for web development, scientific computing, data analysis, artificial intelligence, machine learning, and more.

High-level: Python is a high-level programming language, which means it is designed to be easy to read and write. It has a simple and intuitive syntax that allows programmers to express concepts in fewer lines of code than other languages. Additionally, Python automatically manages low-level details like memory allocation, making it easier to write code without worrying about the underlying system.

Q2. Why is Python called a dynamically typed language?

Ans: Python is called a dynamically typed language because the data types of variables are determined at runtime, rather than being specified at compile time. This means that you do not need to declare the data type of a variable when you first create it in Python, and you can change the data type of a variable by assigning a new value to it of a different type.

Q3. List some pros and cons of Python programming language?

Ans: Pros of Python:

Easy to learn and use: Python has a simple and intuitive syntax, which makes it easy for beginners to learn and use. It is considered one of the most beginner-friendly programming languages.

Large community and libraries: Python has a large and active community of developers who contribute to open-source libraries and frameworks. This means that there is a vast collection of tools and resources available for Python programmers to use.

Multi-purpose: Python is a general-purpose language that can be used for a wide range of tasks, including web development, data analysis, scientific computing, artificial intelligence, machine learning, and more.

Platform independent: Python code can be run on multiple operating systems, including Windows, macOS, and Linux, without the need for any modifications.

High-level language: Python is a high-level language that abstracts away many low-level details, such as memory management, which makes it easier to write code.

Cons of Python:

Slow speed: Python is an interpreted language, which means that it can be slower than compiled languages like C++ or Java. This can be an issue for computationally intensive tasks, such as scientific computing or machine learning.

Weak in mobile computing: Python is not a popular choice for mobile development, as there are limited tools and frameworks available for building mobile applications with Python.

Weak in high-performance computing: Python is not well-suited for high-performance computing, such as complex simulations or rendering of 3D graphics, as it does not offer the low-level control of hardware that some other languages provide.

Dynamic typing can cause errors: Python's dynamic typing can make it easier to introduce errors into your code, as you may accidentally use a variable in a way that is not consistent with its current data type.

Q4. In what all domains can we use Python?

Ans: Python is a versatile and widely-used programming language that can be used in a wide range of domains. Here are some of the most popular domains where Python is used:

Web development: Python can be used to build dynamic websites and web applications, with popular frameworks like Django and Flask.

Data science and analytics: Python is a popular language for data analysis and visualization, with libraries like NumPy, Pandas, and Matplotlib.

Machine learning and artificial intelligence: Python is used extensively in the field of machine learning and AI, with popular libraries like TensorFlow, Keras, and PyTorch.

Scientific computing: Python is a popular language for scientific computing, with libraries like SciPy and BioPython.

Desktop applications: Python can be used to build desktop applications with libraries like PyQt and wxPython.

Network programming: Python has extensive support for network programming, with libraries like Requests and Scapy.

Game development: Python can be used to develop games with libraries like Pygame and PyOpenGL.

Education: Python is a popular language for teaching programming, due to its easy-to-learn syntax and broad range of applications.

Q5. What are variable and how can we declare them?

Ans: A variable is a name that refers to a value, which can be a number, a string, a list, or any other object. Variables are used to store and manipulate data in programs. To declare a variable in Python, we can simply assign a value to a name using the equal sign (=). Here's an example: X=10. 

Q6. How can we take an input from the user in Python?

Ans: In Python, you can take input from the user using the input() function. The input() function prompts the user to enter some input, and then returns that input as a string.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans: the input() function always returns a string, even if the user enters a number or some other type of input. If you want to use the user's input as a number, you'll need to convert it using the appropriate type conversion function (e.g. int() or float()).

Q8. What is type casting?

Ans: Type casting is the process of changing the data type of a value from one type to another. Python provides several built-in functions for type casting, which can be used to convert a value from one data type to another.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans: No, we cannot take more than one input from the user using a single input() function call.If you want to take multiple inputs from the user, you would need to call the input() function multiple times, each time to take a single input. You can store these inputs in separate variables or data structures based on your requirement.

Q10. What are keywords?

Ans: Keywords in Python are a reserved set of words that have a predefined meaning and cannot be used as variable names, function names, or any other identifiers. for example: if,elif,for,and,not,true,false etc.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans: No, we cannot use Python keywords as a variable name because keywords are reserved words that have a predefined meaning in the Python language. Using a keyword as a variable name will result in a syntax error because the interpreter will not be able to interpret the code correctly.

Q12. What is indentation? What's the use of indentaion in Python?

Ans: Indentation is a fundamental feature of the Python programming language and is used to define the scope and structure of code. In Python, indentation is not just a matter of style, but it is a syntactical requirement. The Python interpreter uses indentation to determine the grouping of statements and to recognize the beginning and end of blocks of code.

Q13. How can we throw some output in Python?

Ans: In Python, we can use the print() function to throw output to the console or standard output. The print() function is a built-in function that takes one or more expressions or values as its argument and prints them to the console.

Q14. What are operators in Python?

Ans: In Python, operators are special symbols or keywords that are used to perform specific operations on one or more operands. An operand is a value or variable that an operator acts upon.
There are several types of operators in Python, including:

Arithmetic operators: used to perform mathematical operations like addition (+), subtraction (-), multiplication (*), division (/), modulus (%), and exponentiation (**).

Assignment operators: used to assign values to variables like the equals sign (=), as well as compound assignment operators like +=, -=, *=, /=, and %=.

Comparison operators: used to compare values and return a boolean value like == (equal to), != (not equal to), < (less than), > (greater than), <= (less than or equal to), and >= (greater than or equal to).

Logical operators: used to combine and manipulate boolean values like and, or, and not.

Q15. What is difference between / and // operators?

Ans: In Python, the / operator performs float division, while the // operator performs integer division (also called floor division).

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans:

symbol = "`"
text = "iNeuron"
repeated_text = text * 4
output = symbol * 3+"\n"+"\n"+repeated_text+"\n" + symbol * 3
print(output)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans:

Number = int(input("Please enter a number : "))
if Number % 2 == 0:
    print("The number is even")
else:
    print("The number is odd")

Q18. What are boolean operator?

Ans: In Python, boolean operators are used to evaluate logical expressions and return a boolean value (either True or False). The three boolean operators in Python are: And,Or,Not .

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Ans: 1 or 0 = 1

     0 and 0 = 0

     True and False and True = False

     1 or 0 or 0 = 1

Q20. What are conditional statements in Python?

Ans: Conditional statements in Python are a type of control flow statements that allow you to execute different blocks of code based on whether a certain condition is True or False. The two most common types of conditional statements in Python are the "if" statement and the "if-else" statement.

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans: The code block that follows the "if" statement is executed only if the condition is True. If the condition is False, the code block will follow the "else" statement.If we want to add more conditions to our if-else statement then we have to use "elif". Here is an example:

if x < 0:
    print("x is negative")
elif x == 0:
    print("x is zero")
else:
    print("x is positive")


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans: 
age = int(input("Enter your age : "))
if age >= 18 :
    print("I can vote")
elif age < 18 :
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans: 
numbers = [12, 75, 150, 180, 145, 525, 50]
total=0
for number in numbers :
    if number % 2==0:
        total += number

print("The sum of all the even number in the list is : ",total)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans:1

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
num3 = float(input("Enter third number: "))

if num1 >= num2 and num1 >= num3:
    greatest = num1
elif num2 >= num1 and num2 >= num3:
    greatest = num2
else:
    greatest = num3

print("The greatest number is", greatest)

Ans:2 

numbers = input("Enter 3 numbers separated by comma: ") # input function will help here to take user inputs.
number_list= numbers.split(",") # based on delimiter(,) split method will help to create a list.
number_list_in_int = list(map(int,number_list)) # map() function is used here to convert str to int

greatest= number_list_in_int[0]

for number in number_list_in_int:
    if number>greatest :
        greatest = number

print("The greatest number is : ",greatest)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:

numbers = [12, 75, 150, 180, 145, 525, 50]

for num in numbers:
    if num > 500:
        break 
    if num % 5 == 0 and num <= 150:
        print(num)