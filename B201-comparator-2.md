[↑ Back](./README.md)

# `B201` - Implementing the `Comparator` interface #2

## Highlights

1. Defining nested classes

   1. you need to invoke the constructor via a reference
   1. the nesting instance's members can be accessed from the nested class
   1. useful in rare cases

1. Defining static nested classes

   1. you need to invoke the constructor in a static way
   1. the nesting instance's members can be accessed from the nested class
   1. useful in many cases (when a reusable class has a strong connection with another)

1. Defining anonymous classes

   1. you can give a disposible definition for the abstract methods
   1. useful in many cases (when you need a single instance)

## References

The list is not complete, more references will be added:

1. https://docs.oracle.com/en/java/javase/22/docs/api/java.base/java/util/Objects.html#compare(T,T,java.util.Comparator)

