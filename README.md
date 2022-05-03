# Pseudo-Random Number Generator Testing

## Description of a problem
In mathematics, as well as in real life problems, we often need to use random numbers to solve a problem. For example, a statistician often deals with numbers that, according to the given task, are random, or a student of mathematics who studies a certain phenomenon and needs to carry out a simulation using random numbers. But are they really numbers with such a property? Well, it turns out that not quite. In fact, we are dealing with a pseudo-randomness of numbers, that is, with a set of numbers generated in such a way that it gives the impression of randomness. For such a generation, we currently use algorithms to which a certain generator has been implemented. These are most often algorithms written using a recursive mathematical formula. As we are dealing with recursion we need a zero element that would 'push' the entire construction of the pattern. 

Therefore, each generator requires a specific seed. This seed determines what set will be generated, therefore, knowing the seed of a generator, we are able to obtain exactly the same set (hence the name pseudorandom). However, the question arises, how to check whether the given generated numbers are actually random? 

For such a test, known probabilistic procedures can be used. In such a test, generated sequence is considered a simple sample and we check if it comes from a random sequence. Recall that by a simple sample we mean a sequence of i.i.d. random variables. The sequence of pseudorandom numbers obtained from PRNG is supposed to pretend to be a sequence of independent random variables with a homogeneous distribution. After generating a sample of several thousand, it is difficult to check what it looks like and therefore you have to use statistical methods.

In the project, we will present generators thanks to which it is possible to create a set with pseudorandom properties, as well as to test using special tests based on the probability theory whether the generated numbers actually retain the properties that we would expect


It contains ...
