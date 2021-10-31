## ***In Tests We Trust - TDD with Python***
 Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.
 The test file name should follow the same name of module name. Other thing to care about is the structure. A convention widely used is the AAA: Arrange, Act and Assert.
 * Arrange: you need to organize the data needed to execute that piece of code (input);
 * Act: here you will execute the code being tested (exercise the behaviour);
 * Assert: after executing the code, you will check if the result (output) is the same as you were expecting. 

### TDD Cycle :
**`TDD Cycle`** is an important thing about TDD, the cycle is made by three steps :
1. Write a unit test and make it fail.
2.  Write the feature and make the test pass.
3. Refactor the code.

## ***What does the if **`__name__`** == “**`__main__`**”: do?***
* it will only run when the model itself executed directly.
* And if the model imporded somewhere else it won't executed.

## ***Recursion***
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function. Using recursive algorithm, certain problems can be solved quite easily. Examples of such problems are Towers of Hanoi (TOH), Inorder/Preorder/Postorder Tree Traversals, DFS of Graph, etc.
