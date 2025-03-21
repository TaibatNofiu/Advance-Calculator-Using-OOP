# Advance-Calculator-Using-OOP

Create a class called "Calculator" that contains the following:
A dictionary attribute to store the available mathematical operations and their corresponding functions
A method called "init" that initializes the dictionary with the basic mathematical operations (+, -, *, /) and corresponding functions
A method called "add_operation" that takes in two arguments: the operation symbol and the corresponding function. This method should add the new operation and function to the dictionary.
A method called "calculate" that takes in three arguments: the first number, the operation symbol, and the second number. This method should use the dictionary to determine the appropriate function to perform the calculation. It should also include error handling to check if the operation symbol is valid and if the input values are numbers. If an error is encountered, the method should print an error message and raise an exception.
Create separate functions for the advanced mathematical operations (exponentiation, square root, logarithm) and use the "add_operation" method to add them to the calculator's dictionary.
In the main program, create an instance of the Calculator class, and use a while loop that allows the user to continue performing calculations until they choose to exit.
Use the input() function to get input from the user for the numbers and operation symbol. Use the math library for advanced mathematical operations
Use the isinstance() function to check if the input is a number.
