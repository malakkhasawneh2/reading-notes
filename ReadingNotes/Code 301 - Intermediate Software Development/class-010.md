##What is a ‘call’?

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
## How many ‘calls’ can happen at once?

  code execution in JavaScript synchronous.

##What does LIFO mean?

it means that the last function that gets pushed into the stack is the first to be pop out, when the function return.
## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.
## What is a ‘refrence error’?
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.
## What is a ‘syntax error’?
occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
## What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

## What is a ‘tyep error’?

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## What is a breakpoint?

a breakpoint is an intentional stopping or pausing place in a program, put in place for debugging purposes. It is also sometimes simply referred to as a pause.

