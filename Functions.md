# **_JavaScript Functions_**
* #  a block of code designed to perform a particular task.
* # executed when "something" invokes it (calls it).
* # Defining functions
# 1- Function declarations
# consists of the function keyword, followed by:

* The name of the function.
* A list of parameters to the function, enclosed in parentheses and separated by commas.
* The JavaScript statements that define the function, enclosed in curly brackets, {...}.
* For example:
# function square(number) 
# {
# return number * number;
# }
# 2- Function expressions
# While the function declaration above is syntactically a statement, functions can also be created by a function expression.
* Such a function can be anonymous; it does not have to have a name. 
# For example, the function square could have been defined as:
# const square = function(number) { return number * number }
# var x = square(4) // x gets the value 16
# **_JavaScript Function Syntax_**
* A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
* Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
* The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)
* The code to be executed, by the function, is placed inside curly brackets: {}
 # functionName(parameter1, parameter2, parameter3) {
# // code to be executed
# }
# **_Function Invocation_**
* The code inside the function will execute when "something" invokes (calls) the function:
* When an event occurs (when a user clicks a button)
* When it is invoked (called) from JavaScript code
* Automatically (self invoked)
* You will learn a lot more about function invocation later in this tutorial.
# **_Function Return_**
* When JavaScript reaches a return statement, the function will stop executing.
* If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
# Example
* Calculate the product of two numbers, and return the result:

# var x = myFunction(4, 3);   // Function is called, return value will end up in x
# function myFunction(a, b) {
# return a * b;             // Function returns the product of a and b
# }
# **_Why Functions?_**
* You can reuse code: Define the code once, and use it many times.

* You can use the same code many times with different arguments, to produce different results.

# **Control flow**
* The control flow is the order in which the computer executes statements in a script.

* Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 
* For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not: