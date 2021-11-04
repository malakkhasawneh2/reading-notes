## Big O: Analysis of Algorithm Efficiency
Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:

Running Time (also known as time efficiency / complexity)
The amount of time a function needs to complete.

Memory Space (also known as space efficiency / complexity)
The amount of memory resources a function uses to store data and instructions.

Overview
Big O’s role in algorithm efficiency is to describe the Worst Case of efficiency an algorithm can have in performing it’s job. It specifically looks at the factors mentioned above, which we often refer to as Space and Time. In order to analyze these limiting factors, we should consider 4 Key Areas for analysis:

Input Size

Units of Measurement

Orders of Growth

Best Case, Worst Case, and Average Cas

## Input Size
Input Size refers to the size of the parameter values that are read by the algorithm. This does not simply refer to the number of parameters an algorithm reads, but takes into account the size of each parameter value as well.

Example: If a function uses an array or list as one parameter, then the number of elements within that array or list will directly increase the Input Size of that parameter.

We will use the letter n to refer to the Input Size value.

The higher this number, the more likely there will be an increase to Running Time and Memory Space.

## Units of Measurement
To evaluate a function for Time and Space complexity, we need a way to measure each of these factors.
In order to quantify the Running Time in our analysis, we will consider Three Measurements of time:
1. The time in milliseconds from the start of a function execution until it ends
2. The number of operations that are executed.
3. The number of “Basic Operations” that are executed.


In order to quantify Memory Space, we can consider Four Sources of Memory Usage during function run-time:
1. The amount of space needed to hold the code for the algorithm.
2. The amount of space needed to hold the input data.
3. The amount of space needed for the output data.
4. The amount of space needed to hold working space during the calculation.

# Linked Lists
## To write any kind of algorithms, it's very important to measure the effeciency of the code written.
programmers found a way to measure that by using something called Big O notation.
it has 2 outputs, time and space complexity.
Hey, so, what even is Big O?
Most of us have probably heard the term “Big O Notation”, even if we had no idea what it meant the first time that we heard someone use it. My personal experience with it has always been in the context of designing algorithms (or being asked to evaluate the efficiency of an algorithm). But Big O is really all over and omnipresent within computer science.
The reason for this is that computer science — and effectively, anything that we code — is all about efficiency and tradeoffs. Whether you’re building software as a service, choosing a front end framework, or just trying to make your code DRY and more elegant, that’s what all of us are striving towards: being efficient with our software, and choosing things that are important to what we’re building, all while being aware of the tradeoffs that we’ll ultimately have to make.
The same goes for Big O Notation, but on a much lower level. Big O Notation is a way of evaluating the performance of an algorithm
There are two major points to consider when thinking about how an algorithm performs: how much time it requires at runtime given how much time and memory it needs.

## what is head pointer:
head pointer is a pointer to point/refers the first node in the list


## what is the specification: 
- you can loop through it by for/while/forEach/map loops and check if the Next pointer == Null then stop looping and that means you reach the last node
- time complexity: O(n)
- space complexity: O(1)

- you can create a new node by `Add()` then append the value and the pointers.

## Advantages of Linked List
1. Dynamic Data Structure
2. Insertion and deletion of nodes are really easier.
3. No Memory Wastage


## Disadvantages of Linked List
1. More memory is required to store elements in linked list as compared to array
2. Elements or nodes traversal is difficult in linked list.
3. In linked list reverse traversing is really difficult
