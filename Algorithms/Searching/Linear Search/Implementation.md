# Implementation of Linear Search

In this section, we will provide programming language-specific code examples to implement the linear search algorithm. The implementation examples will help you understand how to apply the linear search algorithm in various programming languages.


<!-- add index for codes - python, C & java -->

<br>
<br>

## Python

Here is an example of how you can implement linear search in Python:

```python
def linear_search(target, data):
    for i in range(len(data)):
        if data[i] == target:
            return i
    return -1

# Example usage:
data = [10, 5, 3, 8, 2, 7]
target = 8
result = linear_search(target, data)
if result != -1:
    print(f"Element {target} found at index {result}")
else:
    print(f"Element {target} not found in the data set")
```

<br>

## Java

Below is an example implementation of linear search in Java:

```java
public class LinearSearch {
    public static int linearSearch(int target, int[] data) {
        for (int i = 0; i < data.length; i++) {
            if (data[i] == target) {
                return i;
            }
        }
        return -1;
    }

    public static void main(String[] args) {
        int[] data = {10, 5, 3, 8, 2, 7};
        int target = 8;
        int result = linearSearch(target, data);
        if (result != -1) {
            System.out.println("Element " + target + " found at index " + result);
        } else {
            System.out.println("Element " + target + " not found in the data set");
        }
    }
}
```

<br>

Feel free to choose the programming language you are comfortable with and implement the linear search algorithm accordingly. The code examples provided above demonstrate how you can use the linear search algorithm to search for a target element in a given data set.


This `Implementation.md` file contains code examples for implementing the linear search algorithm in Python and Java. You can choose the code snippet based on your preferred programming language and use it as a reference to implement linear search in your own projects.
