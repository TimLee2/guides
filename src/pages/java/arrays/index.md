---
title: Java Docs Arrays
---
# Java Array

An Array is used to store a collection of data of similar datatype. Arrays always start with the index of 0.

**Syntax:**

    dataType[] name_of_array;   // preferred way.
    or
    dataType name_of_array[];  //  works but not preferred way

## Code snippets of above syntax:

    double[] list; //preferred way.
    or 
    double list[]; //works but not preferred way.

Note: The style `double list[]` is not preferred as it comes from the C/C++ language and was adopted in Java to accommodate C/C++ programmers.

## Creating Arrays:

    dataType[] name_of_array = new dataType[arraySize];

## Code snippets of the above syntax:

    double[] List = new double[10];

## Another way to create an Array:

    dataType[] name_of_array = {value0, value1, ..., valuek};

## Code snippets of above syntax:

    double[] list = {1, 2, 3, 4};

_Example of code:_

    int[] a = new int[] {4,5,6,7,8}; //declare array
    for (int i=0; i<a.length; i++) //loop goes through each index
    {
        System.out.println(a[i]); //prints the array
    }

![:rocket:](//forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=2 ":rocket:") <a href='https://repl.it/CONn' target='_blank' rel='nofollow'>Run Code</a>

Output:

    4
    5
    6
    7
    8

Source: <a href='https://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html' target='_blank' rel='nofollow'>Java Arrays</a>

## Multidimensional Arrays:

### Declaration:

    dataType[][] name_of_array = new dataType[arraySize][arraySize]; //preferred way
    or
    dataType name_of_array[][] = new dataType[arraySize][arraySize]; //works but not preferred way
    
## Code snippets of above syntax:

    int[][] a = new int[5][2]; //preferred way
    or
    int a[][] = new int[5][2]; //works but not preferred way
    
### Initialization:

    name_of_array[element][element] = value;

## Code snippets of above syntax:

    a[0][0] = 1;
    a[0][1] = 2;
    a[2][1] = 5;
    
