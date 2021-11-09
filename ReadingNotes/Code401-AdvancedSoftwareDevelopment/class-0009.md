## What Are Dunder Methods?
    In Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.

## Object Initialization: __init__
    To construct account objects from the Account class I need a constructor which in Python is the __init__ dunder

## Object Representation: __str__, __repr__
    It’s common practice in Python to provide a string representation of your object for the consumer of your class (a bit like API documentation.) There are two ways to do this using dunder methods:

    1-  __repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous.

    1-  __str__: The “informal” or nicely printable string representation of an object. This is for the enduser.

## Iteration: __len__, __getitem__, __reversed__
    In order to iterate over our account object I need to add some transactions. So first, I’ll define a simple method to add transactions. I’ll keep it simple because this is just setup code to explain dunder methods, and not a production-ready accounting system

## What is probability?
    At the most basic level, probability seeks to answer the question, “What is the chance of an event happening?” An event is some outcome of interest. To calculate the chance of an event happening, we also need to consider all the other events that can occur.

## Z-score
    The Z-score is a simple calculation that answers the question, “Given a data point, how many standard deviations is it away from the mean?” The equation below is the Z-score equation
