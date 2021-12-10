# AVL Tree

##### Explain, what an AVL tree is! Why is it necessary to balance trees?

AVL tree is a height-balanced binary search tree. That means, an AVL tree is also a binary search tree but it is a balanced tree. A binary tree is said to be balanced if, the difference between the heights of left and right subtrees of every node in the tree is either -1, 0 or +1. <br/>
Balancing the tree makes for better search times O(log(n)) as opposed to O(n). As we know that most of the operations on Binary Search Trees proportional to height of the Tree, So it is desirable to keep height small. It ensure that search time strict to O(log(n)) of complexity.
__________________________
##### Explain the algorithm for inserting node into an AVL tree using the sequence 14,17,19,7,5,10,18. Show how the tree looks like after every important step.

* Step 1 - Insert the new element into the tree using Binary Search Tree insertion logic.<br />
* Step 2 - After insertion, check the Balance Factor of every node.<br />
* Step 3 - If the Balance Factor of every node is 0 or 1 or -1 then go for next operation.<br />
* Step 4 - If the Balance Factor of any node is other than 0 or 1 or -1 then that tree is said to be imbalanced. In this case, perform suitable Rotation to make it balanced and go for next operation.<br />
__________________________
**Insert 14** <br />
![image](https://user-images.githubusercontent.com/95900949/145534797-9f1f3d83-4259-43cf-b315-84385e9e77ab.png) <br />
Tree is Balanced <br />
__________________________
**Insert 17**<br />
![image](https://user-images.githubusercontent.com/95900949/145534827-d1ba04b9-ea3b-4eb7-b159-1da369fa892a.png) <br />
Tree is Balanced <br />
__________________________
**Insert 19**<br />
![image](https://user-images.githubusercontent.com/95900949/145534503-6ed9491f-47f3-45a9-aa76-e39a5c2fb74d.png) <br />
Tree is imbalanced <br />
Left Rotation at 17 <br/>
![image](https://user-images.githubusercontent.com/95900949/145535329-3a2c2fcc-f8c0-4bbd-a0b9-234f80d9baee.png) <br />
Tree is Balanced <br />
__________________________
**Insert 7** <br/>
![image](https://user-images.githubusercontent.com/95900949/145535567-29602e5d-d216-480b-b3e6-daf4bca1899c.png) <br />
Tree is Balanced <br />
_________________________
**Insert 5** <br/>
![image](https://user-images.githubusercontent.com/95900949/145535645-554c4724-24f6-48f2-a53f-6c6c968baefd.png) <br />
Tree is imbalanced <br />
Right roatation on 14 <br/>
![image](https://user-images.githubusercontent.com/95900949/145538666-8d5f2a2d-90e8-4764-b685-e37c9f34cada.png) <br />
Tree is Balanced <br />
__________________________
**Insert 10**<br/>
![image](https://user-images.githubusercontent.com/95900949/145538839-7ebc173a-810b-4c8a-88bc-5cf73496dd14.png)<br />
Tree is imbalanced <br />
Doble Right Rotation <br/>
![image](https://user-images.githubusercontent.com/95900949/145538930-7ee66cca-f08a-4c3b-bfa9-5f04601d4df8.png)<br />
Tree is Balanced <br />
__________________________
**Insert 18**<br/>
![image](https://user-images.githubusercontent.com/95900949/145539017-5a0f797b-9ba6-4568-a2ff-87c3c772e1ba.png)
Tree is imbalanced <br />
Double Left rotation at 17 <br/>
![image](https://user-images.githubusercontent.com/95900949/145539159-a2386166-786b-432a-a3dc-0e1f4f7828f7.png) <br/>
Tree is Balanced <br />
__________________________









