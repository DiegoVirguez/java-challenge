# java-challenge

### Largest Range

Write a function that takes in an array of integers and returns an array of length 2 representing the largest range of integers contained in that Array.

The first number in the output array should be the first number in the range, while the second number should be the last number in the range.

A range of numbers is defined as a set of numbers that come right after each other in the set of real integers. For instance, the output array [2,6] represents the range {2,3,4,5,6}, which is a range of length 5. Note that numbers don't need to be sorted or adjacent in the imput array in order to form a range.

### Sample Input

```java
array = [1, 11, 3, 0 ,15, 5, 2, 4, 10, 7, 12, 6]
```

### Sample Output

```java
[0,7]
```

### Main Class

```java
import java.util.*;

class Program {
  public static int[] largestRange(int[] array) {
    // Write your code here.
    return new int[] {};
  }
}
```
### Test Case 1

```java
{
  "array": [8, 4, 2, 10, 3, 6, 7, 9, 1]
}
```

#### Output

```java
{
  [6,10]
}
```
