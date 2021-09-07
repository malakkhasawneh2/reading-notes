# FUNCTIONAL PROGRAMMING

## Functional Programming Concepts

### - What is functional programming?
#### Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

### - What is a pure function and how do we know if something is a pure function?

#### The definition of a pure function is: The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.
### - What are the benefits of a pure function?

#### Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function’s declaration.

### - What is immutability?

#### Unchanging over time or unable to be changed

### - What is Referential transparency?


#### Referential transparency and referential opacity are properties of parts of computer programs.  An expression is called referentially transparent if it can be replaced with its corresponding value (and vice-versa) without changing the program's behavior
#### Node JS Tutorial for Beginners #6 - Modules and require()

### - What is a module?

#### any of a number of distinct but interrelated units from which a program may be built up or into which a complex activity may be analysed.

### - What does the word ‘require’ do?

#### How do we bring another module into the file the we are working in? we need to import the module. we will use the require keyword at the top of the file. The result of require is then stored in a variable which is used to invoke the functions using the dot notation

### - How do we bring another module into the file the we are working in?

#### we need to import the module. we will use the require keyword at the top of the file. The result of require is then stored in a variable which is used to invoke the functions using the dot notation

### - What do we have to do to make a module available?

#### we need to export whatever we need to available outside the module
