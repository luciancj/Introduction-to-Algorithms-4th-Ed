## Step 1

Let us consider Binary Search Trees. A binary search tree is a data structure with the following characteristics:
1. Comprises of nodes where each node has a single predecessor, except the root node (which has node) and can have 0,1 or 2 successors
2. The values in the left-subtree of a node are less than or equal to the values in that node
3. The values in the right-subtree of a node are greater than the values in that node

## Step 2

The advantages of binary search tree are:
1. Operations such as searching an element take O(logN) time
2. Returning the elements in a sorted (ascending/descending order) takes just one pass at the data structure by performing in-order traversal

## Step 3

The disadvantages of a binary search tree are:
1. Inserting/deleting an element also takes O(logN) time, as compared to O(1) of Data structures as Stack/Linked List.
2. Since the basic binary search tree implements no checks on keeping the tree balanced, it might as well lead to a highly unbalaced tree. Such tress defeat the very purpose of Binary Search Trees

## Result
Binary Search Tree:
| Strengths                                                                                                                          | Limitations                                                                                                                                |
|------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| **Fast** basic operation execution, no more than $O(n \log n)$, in average. Maintains **sorted** elements. **Dynamic** allocating. | **Unbalanced** trees, having strictly more nodes for some branch than the other, may yield poor execution; it may result in a linked list. |
