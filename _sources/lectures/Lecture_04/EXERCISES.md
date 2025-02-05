# Exercises for Lecture 4

## Exercise 4.1

  * Create a python library that implements the ```Fraction``` class,
    containing its constructor, the data members to save numerator and denominator,
    and three class method that returns 
    the division between the numerator and the denominator.

## Exercise 4.2

  * Implement a test function of the class inside the library file itself,
    that verifies the output of each method of the class,
    and that prints on screen the value of the numerator and of the denominator of a fraction.

## Exercise 4.3

  * Add to the ```Fraction``` class the overloading of the `+`, `-`, `*`, `/` operations
    in such a way that each of them returns an object of the type ```Fraction```.
  * Add to the test function the call to all the new methods
    and the verification of their behaviour.

## Exercise 4.4

  * Write a python program that reads the sample file [eventi_unif.txt](https://github.com/UnimibFisicaLaboratori/UnimibFisicaLabStatPython/blob/main/book/lectures/Lecture_03/exercises/eventi_unif.txt)
    of Exercise 3.2 and, using the filter function, 
    creates two different sub-sets of events
    containing those larger or smaller than the average respectively,
    using `lambda` functions in the process.
  * Show that the sigma of the two subsets is half the one of the parent sample.    

## Exercise 4.5

  * Write a python program that reads the sample file [```eventi_gauss.txt```](https://github.com/UnimibFisicaLaboratori/UnimibFisicaLabStatPython/blob/main/book/lectures/Lecture_03/exercises/eventi_gauss.txt):
    of Exercise 3.3 and, using the map function, 
    creates the distribution of the squares and cubes of random Gaussian numbers, respectively,
    using `lambda` functions in the process.
  * Plot the distribution of them, together with the original sample one, all in the same frame.
