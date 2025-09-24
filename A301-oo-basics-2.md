[↑ Back](./README.md)

# `A301` - OO Basics #2

Implementing the `Comparable` interface. Creating, populating, and sorting 1D arrays. Using the `final` keyword on fields and variables. Primitive vs. reference arrays. Using command-line arguments. Reading, sorting, and writing the `stdin` and the `stdout` in CSV format.

## Highlights

1. Declaring and using arrays

   1. declaring an array
   1. accessing the array's length
   1. traversing elements
      1. using a classic `for` loop
      1. using an enhanced `for` loop

1. Using the command-line arguments

   1. access the command-line arguments
   1. provide the command-line arguments in IntelliJ IDEA

1. Comparing two values

   1. comparing two `String` objects using the `compareTo()` method
   1. comparing two `int` values using the `Integer.compare()` method
   1. comparing two `double` values using the `Double.compare()` method

1. Implementing `Comparable` interface

   1. the interface's documentation
   1. the syntax for implementing the interface
   1. the return value of the method
      1. `0` in the case of equality
      1. `<0` if `this` goes first
      1. `>0` if the parameter goes first

1. Sorting arrays of `Comparable` elements

1. Using the `final` keyword

   1. on field: making a field read-only
      1. it should be initialized in each constructor
      1. cannot be changed later
   1. on variable: making the variable read-only

## Exercises

### Command-line exercises

Try to implement the previous semester's exercises:

* [`PC200689` - The Curse of Magnitude](https://github.com/INBPA0211L/notes-2024/blob/main/week-08/exercises/args/PC200689.md)
* [`PC200693` - Accuracy Matters!](https://github.com/INBPA0211L/notes-2024/blob/main/week-08/exercises/args/PC200693.md)
* [`PC200701` - Pull the Shortest!](https://github.com/INBPA0211L/notes-2024/blob/main/week-08/exercises/args/PC200701.md)
* [`PC200717` - Avadakedavra](https://github.com/INBPA0211L/notes-2024/blob/main/week-08/exercises/args/PC200717.md)

### Sorting exercises

Try to implement the following exercise sheets. Skip the sorting part. Moreover, you do not have to keep multiple records (objects) in the memory.

1. [`P20301` - Airports](./exercises/P203/P20301.md)
1. [`P20302` - Rollercoasters](./exercises/P203/P20302.md)
1. [`P20303` - LEGO sets](./exercises/P203/P20303.md)

You can enhance the solution by the following directions:

1. always use the most restricted visibility
1. use the `final` keyword when it is possible
1. generate as many code snippets with the IDE as you can
1. create a constructor that receives a CSV line and manages the tokenization

## References

The list is not complete, more references will be added:

1. https://www.baeldung.com/java-command-line-arguments
1. https://www.baeldung.com/java-arrays-guide
1. https://www.baeldung.com/java-compareto

