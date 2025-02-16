# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The bug is in the loop condition, which should be `< arr.length` instead of `<= arr.length`.

## Bug Description

The code attempts to populate an integer array with even numbers. However, the loop in the `main` method runs one iteration too many, causing an `ArrayIndexOutOfBoundsException`. This is a classic off-by-one error.

## Solution

The solution involves correcting the loop condition to use `< arr.length` to properly iterate within the bounds of the array.

## How to reproduce

1.  Clone this repository.
2.  Compile the `bug.java` file using a Java compiler (e.g., `javac bug.java`).
3.  Run the compiled code (e.g., `java MyClass`).
4. Observe the `ArrayIndexOutOfBoundsException`. 

After fixing the error, you'll be able to run the code without error and see the correct output.
