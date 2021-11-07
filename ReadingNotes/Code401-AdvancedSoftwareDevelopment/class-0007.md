## Python Scope
 In programming, the scope of a name defines the area of a program in which you can unambiguously access that name, such as variables, functions, objects, and so on. A name will only be visible to and accessible by the code in its scope. Several programming languages take advantage of scope for avoiding name collisions and unpredictable behaviors. Most commonly, you’ll distinguish two general scopes:

+ Global scope: The names that you define in this scope are available to all your code.

+ Local scope: The names that you define in this scope are only available or visible to the code within the scope. 
![](https://open.oregonstate.education/app/uploads/sites/6/2016/10/II.10_7_both_scope.png)

## Python Scope vs Namespace

In Python, the concept of scope is closely related to the concept of the namespace. As you’ve learned so far, a Python scope determines where in your program a name is visible. Python scopes are implemented as dictionaries that map names to objects. These dictionaries are commonly called namespaces. These are the concrete mechanisms that Python uses to store names. They’re stored in a special attribute called .**dict**.

> > > import sys
> > > sys.**dict**.keys()
> > > dict_keys(['__name__', '__doc__', '__package__',..., 'argv', 'ps1', 'ps2'])


## Using the LEGB Rule for Python Scope

- **local (or function) scope** is the code block or body of any Python function or lambda expression. This Python scope contains the names that you define inside the function. These names will only be visible from the code of the function. It’s created at function call, not at function definition, so you’ll have as many different local scopes as function calls. This is true even if you call the same function multiple times, or recursively. Each call will result in a new local scope being created.

- **Enclosing (or nonlocal) scope** is a special scope that only exists for nested functions. If the local scope is an inner or nested function, then the enclosing scope is the scope of the outer or enclosing function. This scope contains the names that you define in the enclosing function. The names in the enclosing scope are visible from the code of the inner and enclosing functions.

- **Global (or module) scope** is the top-most scope in a Python program, script, or module. This Python scope contains all of the names that you define at the top level of a program or a module. Names in this Python scope are visible from everywhere in your code.

- **Built-in scope** is a special Python scope that’s created or loaded whenever you run a script or open an interactive session. This scope contains names such as keywords, functions, exceptions, and other attributes that are built into Python. Names in this Python scope are also available from everywhere in your code. It’s automatically loaded by Python when you run a program or script.


## The Global Scope
In computer programming, a global variable is a variable with global scope, meaning that it is visible (hence accessible) throughout the program, unless shadowed. The set of all global variables is known as the global environment or global state.

There’s only one global Python scope per program execution. This scope remains in existence until the program terminates and all its names are forgotten. Otherwise, the next time you were to run the program, the names would remember their values from the previous run.


Whenever you assign a value to a name in Python, one of two things can happen:

1. You create a new name
1. You update an existing name


# Big O Notation
Big-O notation is a metrics used to find algorithm complexity. Basically, Big-O notation signifies the relationship between the input to the algorithm and the steps required to execute the algorithm. It is denoted by a big "O" followed by opening and closing parenthesis.

# Rolling Dice Examples:

    from random import randint

    def roll_dice():
        print(f"Number is: {randint (1,6)}")

    roll_dice()
    
    output => Number is **number between 1 and 6**
