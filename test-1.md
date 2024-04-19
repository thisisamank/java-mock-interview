- **Question-1** 
Design a simple Java class ArrayUtils with the following methods:
- **Method:** 
```java
public static char[] sort(char[] array)
```
- **Description:**
This method will take an array of characters and return a new array with the same elements sorted in ascending order. To use this method, you will do:
```java
char[] array = {'b', 'a', 'c'};
char[] sortedArray = ArrayUtils.sort(array);
```
Note: you can use any sorting algorithm you want.

- **Question-2**

Add this method to the ArrayUtils class:
- **Method:** 
```java
public static boolean search(char[] array, char key)
```

- **Description:**
Use binary search to perform the search on the array. The method will return true if the key is found in the array, and false otherwise. To use this method, you will do:
```java
char[] array = {'a', 'b', 'c'};
boolean found = ArrayUtils.search(array, 'b');
```
Note: use recursion to implement binary search
