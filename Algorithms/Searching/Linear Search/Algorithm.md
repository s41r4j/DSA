# Step-by-Step Explanation of Linear Search

Linear search, also known as sequential search, is a simple and straightforward searching algorithm used to find a target element within a collection of data. It sequentially checks each element in the data set until the desired element is found or the entire data set has been searched. The step-by-step explanation below illustrates how linear search works.

<br>

1. **Input**: The linear search algorithm takes two inputs, the target element to be searched for and the collection of data in which the search will be performed.

2. **Start at the Beginning**: The search begins by setting the initial position to the first element of the data set.

3. **Compare with Target**: The algorithm compares the current element at the current position with the target element to determine if they match.

4. **Match Found**: If the current element matches the target element, the search is complete, and the algorithm returns the index or position of the match.

5. **No Match Found**: If the current element does not match the target element, the algorithm moves to the next element in the data set.

6. **End of Data Set**: The algorithm repeats steps 3-5 for each subsequent element until a match is found or the algorithm reaches the end of the data set.

7. **Match Found or End of Data Set**: If a match is found, the algorithm returns the index or position of the match. If the algorithm reaches the end of the data set without finding a match, it indicates that the target element is not present in the data set.

8. **Output**: The linear search algorithm outputs either the index/position of the target element in the data set or a message indicating that the element was not found.

<br>

The linear search algorithm is simple to understand and implement. However, its time complexity is O(n), where n is the size of the data set. This means that in the worst-case scenario, the algorithm may need to traverse the entire data set, resulting in slower performance for large data sets.

Despite its linear time complexity, linear search is still useful in various scenarios, especially when the data set is small or unsorted. It serves as a basic searching technique and forms the foundation for more advanced searching algorithms.

By following the step-by-step explanation of linear search, you can easily understand how the algorithm progresses through each element of the data set until a match is found or the end is reached. This understanding will help you appreciate the simplicity and effectiveness of linear search as a basic search algorithm.


<br>
<br>

## GOTO
- [Follow Learning Path](Pseudocode.md)
- [DSA/Algorithms/Searching/Linear Search](README.md)
