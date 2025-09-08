[↑ Back](./README.md)

# `A102` - Language basics

The goal of this section is to understand the type hierarchy, and be able to read the standard input and write to the standard output. 

## Highlights

1. Primitive types vs. reference types.

   * primitive types: `int`, `char`, `long`, `double`, `boolean`, ...
   * reference types: `String`, `Scanner`, `Integer`, ...

1. Control statements.

   * the classic `for` loop
   * the enhanced `for` (a.k.a foreach)
   * the `while` loop
   * the `do while` loop
   * the `if-else` statement
   * the `switch` statement

1. Writing the standard output using object `System.out` and its methods.

   1. `System.out.print()` - Print something without a newline.
   1. `System.out.println()` - Print something with a newline.
   1. `System.out.printf()` - Inherited behavior from language C.

1. Syntax errors vs. exceptions.

   Check the language's restrictions using the following exercises:

   1. Try to print something after an infinite loop!
   1. Try to print something inside a loop, after a `break` statement!
   1. Try to use an uninitialized `max` or `min` variable!
   1. Try to write a method without returning the expected type!
   1. Try to perform a zero-integer division!
   1. Try to index a non-existing element of an array!

1. Reading the standard input using class `Scanner`.

   * creating (instantiating) a `Scanner` object
   * using the `nextLine()`, `next()`, and `nextInt()` methods
   * using the `hasNextLine()`, `hasNext()`, and `hasNextInt()` methods

1. String concatenation using operator `+`.

   1. Try to read the sides of a shape (rectangle, square, triangle, etc.) and print its area, circumference or perimeter using a verbose message!

1. Using packages

   * default package
   * custom package, the `package` statement
   * the `import` statement

1. Passing VM options

   ```
   -Duser.language=en -Duser.country=US
   ```

## References

1. https://www.baeldung.com/java-syntax
1. https://www.baeldung.com/java-primitives
1. https://www.baeldung.com/java-main-method
1. https://www.baeldung.com/java-control-structures
1. https://www.baeldung.com/java-loops
1. https://www.baeldung.com/java-packages
1. https://www.baeldung.com/java-command-line-arguments

## Sample codes

TODO