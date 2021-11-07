# How to use the Random Module in Python

## Random functions

- Randint:

    What is random Randint?
randint() is an inbuilt function of the random module in Python3. The random module gives access to various useful functions and one of them being able to generate random numbers, which is randint().
- Random:

    If you want a larger number, you can multiply it.
    For example, a random number between 0 and 100:

    import random

    random.random() * 100

- Choice

    The choice() method returns a randomly selected element from the specified sequence. The sequence can be a string, a range, a list, a tuple or any other kind of sequence.

- Shuffle

    random provides shuffle() that shuffles the original list in place, and sample() that returns a new list that is randomly shuffled. sample() can also be used for strings and tuples.

- Randrange

    What does random Randrange do in Python?
    The random. randrange() function returns a random integer number within the given range.
    
    ## What is Risk Analysis in Software Testing and how to perform it?

The probability of any unwanted incident is defined as Risk. In Software Testing, risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test. After that, the process of assigning the level of risk is done. The categorization of the risks takes place, hence, the impact of the risk is calculated.

## Why use Risk Analysis?

In any software, using risk analysis at the beginning of a project highlights the potential problem areas. After knowing about the risk areas, it helps the developers and managers to mitigate the risks. When a test plan has been created, risks involved in testing the product are to be taken into consideration along with the possibility of the damage they may cause to your software along with solutions.
Now, you might think what could be the possible risks that you could encounter? Well here is a list:

1. Use of new hardware
2. Use of new technology
3. Use of new automation tool
4. The sequence of code
5. Availability of test resources for the application

### Risk Identification

There are different sets of risks included in the risk identification process. Those are as follows:

1. Business Risks: This risk is the most common risk associated with our topic. It is the risk that may come from your company or your customer, not from your project.

2. Testing Risks: You should be well acquainted with the platform you are working on, along with the software testing tools being used.

3. Premature Release Risk: a fair amount of knowledge to analyze the risk associated with releasing unsatisfactory or untested software is required

4. Software Risks: You should be well versed with the risks associated with the software development process.

### Risk Assessment

In the risk analysis process, these steps prove to be the most important one. It is said that this step is way too complex and should be tackled with the utmost care. After risk identification, assessment has to be dealt programmatically. There are a few perspectives on risk assessment. Read on!

## Risk Assessment
**A risk assessment** is a process to identify potential hazards and analyze what could happen if a hazard occurs.

## The perspective of Risk Assessment
- **Effect:** To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.

- **Cause:** To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.

- **Likelihood:** To assess risk by Likelihood is to say that there is a probability that a requirement won’t be satisfied.

# Test Coverage
Coverage.py is a tool for measuring code coverage of Python programs. It monitors your program, noting which parts of the code have been executed, then analyzes the source to identify code that could have been executed but was not. Coverage measurement is typically used to gauge the effectiveness of tests.

# Big O Notation
Big-O notation is a metrics used to find algorithm complexity. Basically, Big-O notation signifies the relationship between the input to the algorithm and the steps required to execute the algorithm. It is denoted by a big "O" followed by opening and closing parenthesis.


# Python Random
For integers, there is uniform selection from a range. For sequences, there is uniform selection of a random element, a function to generate a random permutation of a list in-place, and a function for random sampling without replacement.

Class Random can also be subclassed if you want to use a different basic generator of your own devising: in that case, override the random(), seed(), getstate(), and setstate() methods. Optionally, a new generator can supply a getrandbits() method — this allows randrange() to produce selections over an arbitrarily large range.

## Bookkeeping functions
**random.seed(a=None, version=2)**
Initialize the random number generator.

**random.getstate()**
Return an object capturing the current internal state of the generator. This object can be passed to setstate() to restore the state.

**random.setstate(state)** state should have been obtained from a previous call to getstate(), and setstate() restores the internal state of the generator to what it was at the time getstate() was called.

## Functions for bytes
random.randbytes(n)
Generate n random bytes.

## Functions for integers
**random.randrange(stop)**
**random.randrange(start, stop[, step])**
Return a randomly selected element from range(start, stop, step). This is equivalent to choice(range(start, stop, step)), but doesn’t actually build a range object.

**random.randint(a, b)**
Return a random integer N such that a <= N <= b. Alias for randrange(a, b+1).

**random.getrandbits(k)**
Returns a non-negative Python integer with k random bits. This method is supplied with the MersenneTwister generator and some other generators may also provide it as an optional part of the API. When available, getrandbits() enables randrange() to handle arbitrarily large ranges.


## Functions for sequences
**random.choice(seq)** Return a random element from the non-empty sequence seq. If seq is empty, raises IndexError.

**random.choices(population, weights=None, , cum_weights=None, k=1)**
Return a k sized list of elements chosen from the population with replacement. If the population is empty, raises IndexError.

**random.shuffle(x[, random])** Shuffle the sequence x in place.

**random.sample(population, k, *, counts=None)**
Return a k length list of unique elements chosen from the population sequence or set. Used for random sampling without replacement.

## Real-valued distributions

**random.random()**
Return the next random floating point number in the range [0.0, 1.0).

**random.uniform(a, b)**
Return a random floating point number N such that a <= N <= b for a <= b and b <= N <= a for b < a.


**random.triangular(low, high, mode)**
Return a random floating point number N such that low <= N <= high and with the specified mode between those bounds. The low and high bounds default to zero and one. The mode argument defaults to the midpoint between the bounds, giving a symmetric distribution.

**random.betavariate(alpha, beta)**
Beta distribution. Conditions on the parameters are alpha > 0 and beta > 0. Returned values range between 0 and 1.

**random.expovariate(lambd)**
Exponential distribution. lambd is 1.0 divided by the desired mean. It should be nonzero. (The parameter would be called “lambda”, but that is a reserved word in Python.) Returned values range from 0 to positive infinity if lambd is positive, and from negative infinity to 0 if lambd is negative.

**random.gammavariate(alpha, beta)**
Gamma distribution. (Not the gamma function!) Conditions on the parameters are alpha > 0 and beta > 0.

**random.gauss(mu, sigma)** Normal distribution, also called the Gaussian distribution. mu is the mean, and sigma is the standard deviation. This is slightly faster than the normalvariate() function defined below.

**random.lognormvariate(mu, sigma)**
Log normal distribution. If you take the natural logarithm of this distribution, you’ll get a normal distribution with mean mu and standard deviation sigma. mu can have any value, and sigma must be greater than zero.

**random.normalvariate(mu, sigma)**
Normal distribution. mu is the mean, and sigma is the standard deviation.

**random.vonmisesvariate(mu, kappa)**
mu is the mean angle, expressed in radians between 0 and 2*pi, and kappa is the concentration parameter, which must be greater than or equal to zero. If kappa is equal to zero, this distribution reduces to a uniform random angle over the range 0 to 2*pi.

**random.paretovariate(alpha)**
Pareto distribution. alpha is the shape parameter.

**random.weibullvariate(alpha, beta)**
Weibull distribution. alpha is the scale parameter and beta is the shape parameter.

## Alternative Generator
**class random.Random([seed])** Class that implements the default pseudo-random number generator used by the random module.

**class random.SystemRandom([seed])** Class that uses the os.urandom() function for generating random numbers from sources provided by the operating system. Not available on all systems. Does not rely on software state, and sequences are not reproducible. Accordingly, the seed() method has no effect and is ignored. The getstate() and setstate() methods raise NotImplementedError if called.
