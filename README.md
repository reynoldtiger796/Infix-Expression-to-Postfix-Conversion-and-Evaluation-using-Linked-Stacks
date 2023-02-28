# Infix-Expression-to-Postfix-Conversion-and-Evaluation-using-Linked-Stacks
Write a C++ program that reads an infix expression from the user, converts it to postfix notation using a linked stack, and then evaluates the postfix expression to obtain its value. The program should make use of classes to implement the linked stack data structure.

Requirements

The program should ask the user to enter an infix expression consisting of numbers and the operators +, -, *, /, and ^ (exponentiation).
The program should then convert the infix expression to postfix notation using a linked stack.
The program should then evaluate the postfix expression to obtain its value using a linked stack.
The program should display the value of the postfix expression to the user.
The program should handle any errors that may occur during the conversion or evaluation process.

Guidelines

You should implement a class for the linked stack data structure. The class should have the following public member functions:

push() - adds a new element to the top of the stack.

pop() - removes the top element from the stack.

top() - returns the value of the top element of the stack.

empty() - returns a boolean indicating whether the stack is empty.

You should implement a separate function for each of the following tasks:

infixToPostfix() - converts an infix expression to postfix notation using a linked stack.

evaluatePostfix() - evaluates a postfix expression using a linked stack.

You may assume that the input infix expression is well-formed (i.e., it contains a valid arithmetic expression), but you should handle any errors that may occur during the conversion or evaluation process (e.g., division by zero).

You should test your program with several different input infix expressions, including expressions with multiple operators and parentheses.

You should submit your program code, along with a brief report that describes how you implemented the program and how it works.
