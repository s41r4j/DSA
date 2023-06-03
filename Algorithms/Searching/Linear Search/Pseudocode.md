# Language-Agnostic Pseudocode for Linear Search

The linear search algorithm is a simple searching algorithm that iterates through a collection of elements to find a specific target element. The following pseudocode provides a language-agnostic representation of the linear search algorithm:

<br>

## Pseudocode
```
LinearSearch(target, data):
    for i = 0 to length(data) - 1 do:
        if data[i] equals target then:
            return i // Target element found at index i
    return -1 // Target element not found in the data set
```

<br>

### Let's break down the pseudocode step-by-step:

1. The `LinearSearch` function takes two parameters: `target` and `data`. 
2. It initializes a loop that iterates from index `0` to `length(data) - 1`.
3. Inside the loop, it checks if the element at index `i` of `data` is equal to the `target` element.
4. If a match is found, the function returns the index `i`, indicating that the target element is found at that position.
5. If no match is found after traversing the entire `data` set, the function returns `-1`, indicating that the target element is not present.

<br>

This language-agnostic pseudocode provides a clear and concise representation of the linear search algorithm. You can easily translate this pseudocode into your preferred programming language to implement linear search in your projects.

You can find the complete implementation of the linear search algorithm in various programming languages using the provided pseudocode in the Implementation section.


<br>
<br>

## GOTO
- [Follow Learning Path](implementation.md)
- [DSA/Algorithms/Searching/Linear Search](README.md)
