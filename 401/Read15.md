# Trees

> ## Questions

1. What is a node? 

2. What is a root? 

3. What is prioritized during depth first transversal? 

4. What is the most common way to transverse through a tree? 

5. What does pre-order mean? 

6. What happens if both the root.left and root.right return null? 

7. What will the program do if it finds that F doesn't have any children? 

8. How does breadth first transversal iterate through the tree? 

9. Is there any specific sorting order for a binary tree? 

10. What is a K-ary Tree?

11. What does K refer to? 


> ## Answers

1. Node - A Tree node is a component which may contain its own values, and references to other nodes

2. Root - The root is the node at the beginning of the tree

3. Depth first traversal is where we prioritize going through the depth (height) of the tree first.

4. The most common way to traverse through a tree is to use recursion. 

5. Pre-order means that the root has to be looked at first.

6. The program will look for both a root.left and a root.right. Both will return null, so it will end the execution of that method call.

7. The program will find that F does not have any children and it will make its way back up the call stack up to C.

8. Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.

9. There is no specific sorting order for a binary tree. 

10.  If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree.

11. In this type of tree we use K to refer to the maximum number of children that each Node is able to have.

[Return Home](../README.md)
