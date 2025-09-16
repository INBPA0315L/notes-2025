[↑ Back](./README.md)

# `A201` - OO Basics #1

Defining classes. Defining fields. Overriding methods inherited from the `Object` class. Defining constructors. Reading and writing the `stdin` and the `stdout` in CSV format.

## Highlights

1. Conversion between `String` and primitive types

   Try to use the following methods to convert to/from type `String`:

   1. `Double.parseDouble()`
   1. `Integer.parseInt()`
   1. `String.valueOf()`
   1. `String.format()`

1. Defining classes

   1. Placing one or more classes in the same source code.
   1. Defining custom classes in custom packages.

1. Defining instance-level fields

1. Instantiating objects

   1. references
   1. objects
   1. printing objects to the standard output
   1. assigning fields' values
   1. accessing fields' values

1. Visibility levels of fields

   1. the default (a.k.a package) visibility
   1. the `public` visibility
   1. the `protected` visibility
   1. the `private` visibility

1. Defining constructors

   1. creating an all-args constructor
   1. creating a constructor having a default value
   1. creating the no-args (default) constructor explicitly
   1. understanding the implicit constructor
   1. using the `this` keyword

1. Type hierarchy

   1. the `Object` class
   1. the `Object` class's [JavaDoc page](https://docs.oracle.com/en/java/javase/22/docs/api/java.base/java/lang/Object.html)

1. Overriding the `toString()` method

   1. the basic representation of the instances
   1. auto-generating the body
   1. creating a custom body
   1. implicit vs. explicit call of the `toString()` method
   1. the `@Override` annotation

1. Defining and using *getters*
   
1. Defining and using *setters*

1. Overriding the `equals()` method

   1. testing the `==` and `!=` operators
   1. understanding references vs. objects
   1. generating the `equals()` method, understanding it
   1. using the `Objects.equals()` method
   1. understanding the `getClass()` method

1. Overriding the `hashCode()` method

   1. understanding the reason
   1. generating the `hashCode()` method

1. Reading CSV format from the standard input

   1. using the method `String.split()`
   1. using a `Scanner` instance

## Exercises

Try to implement the following exercise sheets. Skip the sorting part. Moreover, you do not have to keep multiple records (objects) in the memory.

1. [`P20201` - Airports](./exercises/P202/P20201.md)
1. [`P20202` - Rollercoasters](./exercises/P202/P20202.md)
1. [`P20203` - LEGO sets](./exercises/P202/P20203.md)

You can enhance the solution by the following directions:

1. always use the most restricted visibility
1. generate as many code snippets with the IDE as you can

## References

The list is not complete, more references will be added:

1. https://www.baeldung.com/java-access-modifiers
1. https://www.baeldung.com/java-object-tostring-vs-string-valueof
1. https://www.baeldung.com/java-equals-method-operator-difference
1. https://www.baeldung.com/java-comparing-objects
1. https://www.baeldung.com/string/split
