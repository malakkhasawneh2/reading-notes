## Read & Write Files in Python

One of the most common tasks that you can do with Python is reading and writing files. Whether it’s writing to a simple text file, reading a complicated server log, or even analyzing raw byte data, all of these situations require reading or writing a file.

**Files on most modern file systems are composed of three main parts :**

1. Header : metadata about the contents of the file (file name, size, type, and so on)

2. Data: contents of the file as written by the creator or editor

3. End of file (EOF): special character that indicates the end of the file

### File Paths

*When you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file. It’s broken up into three major parts :*

1. Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)

2. File Name: the actual name of the file

3. Extension: the end of the file path pre-pended with a period (.) used to indicate the file type .

**Exceptions versus Syntax Errors**

Syntax errors occur when the parser detects an incorrect statement.

The AssertionError Exception
Instead of waiting for a program to crash midway, you can also start by making an assertion in Python. We assert that a certain condition is met. If this condition turns out to be True, then that is excellent! The program can continue. If the condition turns out to be False, you can have the program throw an AssertionError exception .


* A try clause is executed up until the point where the first exception is encountered.

* Inside the except clause, or the exception handler, you determine how the program responds to the exception.

* You can anticipate multiple exceptions and differentiate how the program should respond to them.

* Avoid using bare except clauses.
