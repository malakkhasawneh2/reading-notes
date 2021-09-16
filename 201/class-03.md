# ***Lists in Html***
# We have :
* Ordered lists
  - each item in the list is
numbered 
* Unordered lists
  - e lists that begin with a bullet point
* Definition lists
  - made up of a set of terms along with the
definitions for each of those terms.
____________
# Ordered Lists
* < ol >
  - The ordered list is created with the < ol > element
* < li >
  - Each item in the list is placed between an opening < li > tag and a closing < /li > tag
  <img src="https://i.ytimg.com/vi/5tJBpZjMAbw/maxresdefault.jpg">
  ________
  # Unordered Lists
  * < ul >
    -The unordered list is created with the < ul > element.
      -specify the type of bullet point
      <img src="https://i.ytimg.com/vi/5tJBpZjMAbw/maxresdefault.jpg">
____________
# Definition Lists
* < dl >
  -  usually consists of a series of terms and their definitions
    - Inside the < dl> element you will usually see pairs of < dt> and < dd> elements.
* < dt>
  - This is used to contain the term being defined 
* < dd>
  - This is used to contain the definition. 

 <img src="https://www.wikihow.com/images/thumb/c/c7/Define-a-Definition-List-in-HTML-Step-11.jpg/v4-460px-Define-a-Definition-List-in-HTML-Step-11.jpg.webp">
        
__________________
# Nested List
* You can put a second list inside an < li> element to create a sublist or nested list.

<img src="https://i.stack.imgur.com/rqAiC.jpg">
____________
____________

# ***Boxes In CSS***
# BOX DIMensions
 - width, height
   - By default a box is sized just big enough to hold its contents. 
    - To set your own dimensions for a box you can use the height and width properties.
    - The most popular ways to specify the size of a box are to use pixels, percentages, or ems

<img src="https://user.oc-static.com/upload/2018/05/17/15265909024573_p1c5-1.png">

# Limiting Width
- min-width, max-width
   - the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, 
   - the max-width property indicates the maximum width a box can stretch to when the browser window is wide.
   - helpful properties to ensure that the content of pages are legible

<img src="https://i.stack.imgur.com/k9vLo.png">

# Limiting Height
* min-height, max-height
   - y that you might want to limit the width of a box on a page, you may also want to limit the height of it
# Overflowing Content
* overflow
  ##### tells the
browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
* hidden 
  - This property simply hides any extra content that does not fit in the box.
* scroll
  - This property adds a scrollbar to the box so that users can scroll to see the missing content  
 _______________
 # Border, Margin & Padding
 <img src="https://cssgurubd.files.wordpress.com/2015/01/box-model_of_css3.png">
  
# **Border** 
# border-width 
* used to control the width of a border
* You can control the individual size of borders using four separate properties:
  - border-top-width
  - border-right-width
  - border-bottom-width
  - border-left-width

# border-style
* control the style
* This property can take the following values:
   - **solid** a single solid line
   - **dotted** a series of square dots 
   - **dashed** a series of short lines  
   - **double** two solid lines (the value of the border-width property creates the sum of the two lines)
   - **groove** appears to be carved into the page
   - **ridge** appears to stick out from the page
   - **outset** looks like it is coming out of the screen
   - **hidden / none** no border is shown

# Shorthand
* The border property allows you to specify the width, style and color of a border in one property (and the values should be coded in that specific order).

# **Padding**
*  allows you to specify how much space should appear between the content of an element and its border
# **Margin**
* controls the gap between boxes.
_____________
# **Change Inline/Block**
## display
* The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.
* The values this property can take are:
  - **inline** This causes a block-level element to act like an inline element.
  - **block** This causes an inline element to act like a block-level element.
  - **inline-block** This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.
  - **none** This hides an element from the page. In this case, the element acts as though it is not on the page at all

# **Hiding Boxes**
* **visibility** property allows you to hide boxes from users but It leaves a space where the element would have been.
* This property can take two values:
  - **hidden** This hides the element.
  - **visible** This shows the element.

# **Border Images**
* **border-image** property applies an image to the border of any box. It takes a background image and slices it into nine pieces. 
* This property requires three
pieces of information:
  - 1: The URL of the image
  - 2: Where to slice the image
  - 3: What to do with the straight
* the possible values are:
   - stretch stretches the image
   - repeat repeats the image
   - round like repeat but if the tiles do not fit exactly, scales the tile image so they will

# **Box Shadows**
* **box-shadow** property allows you to add a drop shadow around a box
* It must use at least the first of these two values as well as a color:
  - **Horizontal offset** Negative values position the shadow to the left of the box.
  - **Vertical offset** Negative values position the shadow to the top of the box.
  - **Blur distance** If omitted, the shadow is a solid line like a border.
  - **Spread of shadow** If used, a positive value will cause the shadow to expand in all directions, and a negative value will make it contract.

__________________
__________________
# ***ARRAYS*** 
* a special type of variable. It doesn't just store one value; it stores a list of values.
* You create an array and give it a name just like you would any other variable 
* values are assigned to the array inside a pair of square brackets, and each value is separated by a comma
* The values in the array do not need to be the same data type
# VALUES IN ARRAYS
* NUMBERING ITEMS IN
AN ARRAY Each item in an array is automatically given a number called an index
* ACCESSING ITEMS IN AN ARRAY To retrieve the third item on the list
* NUMBER OF ITEMS IN AN ARRAY Each array has a property called length, which holds the number of items in the array.
# ACCESSING & CHANGING VALUES IN AN ARRAY
* You can change the value of an item an array by selecting it and assigning it a new value just as you would any other variable (using the equals sign and the new value for that item). 
__________________
# ***looping***
## If ... else

<img src="https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-statement.png">


## switch statement
<img src="https://i.ytimg.com/vi/a9Q765OAKT4/maxresdefault.jpg">
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


  
