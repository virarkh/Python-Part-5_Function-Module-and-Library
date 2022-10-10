# Function-and-Modules

## Function
- In Python, a function is a group of related statements that performs a specific task.
- Functions help break our program into smaller and modular chunks. As our program grows larger and larger, functions make it more organized and manageable.
- Furthermore, it avoids repetition and makes the code reusable.
#### Syntax of Function
def function_name(parameters):
> """docstring"""
>> statement(s)

Above shown is a function definition that consists of the following components.
- Keyword def that marks the start of the function header.
- A function name to uniquely identify the function.
- Parameters (arguments) through which we pass values to a function. They are optional.
- A colon (:) to mark the end of the function header.
- Optional documentation string (docstring) to describe what the function does.
- One or more valid python statements that make up the function body. Statements must have the same indentation level (usually 4 spaces).
- An optional return statement to return a value from the function.
#### String in function
We can also use string in function statement.
## Return
The return statement is used to exit a function and go back to the place from where it was called.
#### Syntax of return
return [experession_list]
This statement can contain an expression that gets evaluated and the value is returned. If there is no expression in the statement or the return statement itself is not present inside a function, then the function will return the None object.
## Pass by reference vs value
- Passing by reference means the called functions' parameter will be the same as the callers' passed argument (not the value, but the identity - the variable itself).
- Pass by value means the called functions' parameter will be a copy of the callers' passed argument.
## Local vs Global Variables
This means that local variables can be accessed only inside the function in which they are declared, whereas global variables can be accessed throughout the program body by all functions. When you call a function, the variables declared inside it are brought into scope.

## Modules
A Python module is a file containing Python definitions and statements. A module can define functions, classes, and variables. A module can also include runnable code. Grouping related code into a module makes the code easier to understand and use. It also makes the code logically organized.
<li>Math Module</li>
<li>Random Module</li>
<li>Date Module</li>
<li>Numpy Module</li>
<li>sys Module</li>
<li>io Module</li>
