# Daniel's Gotcha List
Pull requests welcome!
- `for (int i = 0; i < n.length; i *= 2)` <- whenever there's multiplication like this, there's probably logs involved in the order
- Know the different binary tree terms, e.g. full, complete, etc.
- Also know red-black trees
- Inserting into binary trees will degenerate if the data follows a zig-zag pattern
- Modifying the size of a container while iterating over it using an indexed for loop causes a logic error 
- When implementing hash table insert, remember to take the absolute value of the hashCode
- Recursive backtracking through graphs will have infinite recursion if you don't detect cycles
- On DP problems, when setting the initial condition, watch out for the size of the input - you might need an edge case
