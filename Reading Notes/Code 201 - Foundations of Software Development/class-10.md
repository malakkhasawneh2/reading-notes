# Error Handling & Debugging

## ORDER OF EXECUTION 
* To find the source of an error, it helps to know how scripts are processed.
* execution contexts
  -  one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 
  <img src="img/j9.PNG">

# The stack
* The js interpreter processes one line of code at a time When statement needs data from anather function it stacks the new function on top of the current task
# EXECUTION CONTEXT & HOISTING
  <img src="img/j10.PNG">

# ERROR OBJECTS 
<img src="img/j11.PNG">

# ERROR OBJECTS CONTINUED
<img src="img/j12.PNG">
<img src="img/j13.PNG">
<img src="img/j14.PNG">
<img src="img/j15.PNG">

# A DEBUGGING WORKFLOW
<img src="img/j16.PNG">

# BROWSER DEV TOOLS & JAVASCRIPT CONSOLE 
* The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 
* These two pages show instructions for opening the console in all of the main browsers

<img src="img/j17.PNG">
<img src="img/j18.PNG">

# HOW TO LOOK AT ERRORS IN CHROME 
* The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter
<img src="img/j19.PNG">

# HOW TO LOOK AT ERRORS IN FIREFOX
<img src="img/j20.PNG">

# TYPING IN THE CONSOLE IN CHROME 
<img src="img/j21.PNG">

# HANDLING EXCEPTIONS
* If you know your code might fail, use try, catch, and finally. Each one is given its own code block. 
<img src="img/j22.PNG">

# DEBUGGING TIPS 
<img src="img/j23.PNG">



