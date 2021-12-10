Solution
---

##### Explain, what an AVL tree is! Why is it necessary to balance trees?

AVL tree is a height-balanced binary search tree. That means, an AVL tree is also a binary search tree but it is a balanced tree. A binary tree is said to be balanced if, the difference between the heights of left and right subtrees of every node in the tree is either -1, 0 or +1. 
Balancing the tree makes for better search times O(log(n)) as opposed to O(n). As we know that most of the operations on Binary Search Trees proportional to height of the Tree, So it is desirable to keep height small. It ensure that search time strict to O(log(n)) of complexity.

##### Explain the algorithm for inserting node into an AVL tree using the sequence 14,17,19,7,5,10,18. Show how the tree looks like after every important step.

Step 1 - Insert the new element into the tree using Binary Search Tree insertion logic.
Step 2 - After insertion, check the Balance Factor of every node.
Step 3 - If the Balance Factor of every node is 0 or 1 or -1 then go for next operation.
Step 4 - If the Balance Factor of any node is other than 0 or 1 or -1 then that tree is said to be imbalanced. In this case, perform suitable Rotation to make it balanced and go for next operation.

*Insert 14* 

Tree is Balanced
