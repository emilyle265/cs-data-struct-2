# Discussion questions

### Recursion

1. In your own words, what is recursion?
    It's when a function calls itself from within itself. It's similar to a loop.
2. Why is it necessary to have a base case?
    A base case is necessary to prevent infinite recursion where it keeps calling itself.

### Graphs

1. What is a graph?
    A group is a representation of associations using nodes and vertices.
2. How is a graph different from a tree?
    Graphs can have loops and doesn't have to be directed or have a hierarchy.
3. Give an example of something that would be good to model with a graph.
    Muni routes.

### Performance of Different Data Structures

Data Structure | Index | Search | Add-R | Add-L  | Pop-L | Pop-R
----------------|-------|-------|-------|-------|-------|--------
Python List (Array) | O(1) | O(n) | O(1) | O(n) | O(n) | O(1)       
Linked List | O(n) | O(n) | O(1) | O(1) | O(1) | O(n)          
Doubly-Linked List | O(n) | O(n) | O(1) | O(1) | O(1) | O(1)   
Queue (as Array) | X | X | O(1) | X | O(n) | X 
Queue (as LL or DLL) | X | X | O(1) | X | O(1) | X
Stack (as Array, LL, or DLL) | X | X | O(1) | X | X | O(1)   
Deque (as DLL) | X | X | O(1) | O(1) | O(1) | O(1)  

Data Structure | Get | Add | Delete | Iterate | Memory
----------------|-------|-------|-------|-------|-------
Dictionary (Hash Map) | O(1) | O(1) | O(1) | O(n) | medium
Set (Hash Map) | O(1) | O(1) | O(1) | O(n) | medium
Binary Search Tree | O(log n) | O(log n) | O(log n) | O(n) | small
Tree | O(n) | O(1) | O(1) | O(n) |  small

### Sorting

1. Describe in words how the Bubble Sort algorithm works.
    You compare the first two indeces in a list, check if the first is bigger than the next.
    If it is, switch so the bigger one is farther to the right. If not, keep the indices where they are. Then, you move down one index for the two index you're next going to compare. You keep doing this until all the things in the list are sorted from smallest to largest.
2. Describe in words how the Merge Sort algorithm works.
    Merge sort breaks a list into parts until a list has only 1 index. Then, all the lists merge back in sorted order.
3. Describe in words how the Quick Sort algorithm works.
    You select a pivot point, and then sort the list into buckets of lower and higher values.

