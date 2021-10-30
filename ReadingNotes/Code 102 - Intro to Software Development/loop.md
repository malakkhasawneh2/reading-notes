# **Operators**
# _JavaScript has the following types of operators:_
* Assignment operators
* Comparison operators
* Logical operators
* String operators

# _**Assignment operator**_

* assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.
# _**Comparison operators**_
* its operands and returns a logical value based on whether the comparison is true. 
* The operands can be numerical, string, logical, or object values. 
* if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. 
* The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. 
* These operators do not attempt to convert the operands to compatible types before checking equality.
* Equal (==)	Returns true if the operands are equal.	
* ex . 
### 3 == var1 
### "3" == var1
### 3 == '3' 
* Strict equal (===)	Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.
* ex .
###	3 === var1
* Greater than (>)	Returns true if the left operand is greater than the right operand.	
### var2 > var1
### "12" > 2
* Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand.	
### var2 >= var1
### var1 >= 3
* Less than (<)	Returns true if the left operand is less than the right operand.
###	var1 < var2
### "2" < 12
* Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand.
###	var1 <= var2
### var2 <= 5
# _**Logical operators**_
* Are typically used with Boolean (logical) values; when they are, they return a Boolean value. 
* the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. 
* **Logical AND (&&)**	
### expr1 && expr2	Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.
* **Logical OR (||)**	
### expr1 || expr2	Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.
* **Logical NOT (!)**	
### !expr	Returns false if its single operand that can be converted to true; otherwise, returns true.
# _**String operators**_
* ### In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.
# For example
# console.log('my ' + 'string')
# console logs the string "my string".
# _**Loops and iteration**_
#  Easy way to do something repeatedly. 
# for statement
### A for loop repeats until a specified condition evaluates to false. 
### A for statement looks as follows:

# for ([initialExpression]; 
# [conditionExpression] 
# [incrementExpression])
# When a for loop executes, the following occurs:
### The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
### The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
### The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
## If present, the update expression incrementExpression is executed.
## Control returns to Step 2.
# _**while statement**_
## A while statement executes its statements as long as a specified condition evaluates to true. 
# A while statement looks as follows:
# while (condition)
 # statement
### If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
## The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.