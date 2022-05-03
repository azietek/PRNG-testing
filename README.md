# Pseudo-Random Number Generator Testing

## Description of a project
Pseudorandom number generator abbreviated as PRNG is an algorithm, which, by means of deterministic methods, generates numbers that we can say that they appear to be random. We say that the numbers derived from the generated sequence are pseudorandom because they are not a coincidence, but the result of algorithmic calculations. Each generator needs a seed for its implementation, i.e. a number that uniquely defines the generated sequencing of numbers. Repeating the generation with the same seed we will get exactly the same string. PRNG are widely used in simulations, cryptography or computer games.

To assess the quality of the generator, we subject it to various tests. Generator tests allow you to pre-determine whether the generated values are pseudorandom. All of them ultimately return p-values, thanks to which we can assess whether the generated string is actually random.

Each test returns a p-value. If it is very close to 0 or 1 (let's say < 0.0001 | > 0.9999) we can assume that this generator is not good. However, there is a chance that this value will be reached and the generator is good. Therefore, for this purpose, we use second level testing, which consists in re-testing many returned p-values.


## Content
Repository contains:

- ```programmes``` directory that contains code of each alghoritm. There is two test (with ```_test.py``` ending) and one generator

- ```seeds``` directory that contains one ```.csv``` file with sample seeds

- ```docs``` diredtory that contains short description and sample usage of tests and generator in  ```programmes``` directory


# Usage
You can find usage of every program in ```docs``` directory or by typing ```-h``` in console for help.


