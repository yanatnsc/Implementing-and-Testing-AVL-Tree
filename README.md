# Implementing-and-Testing-AVL-Tree
## Main.java
Doing a simple sanity check in this class to generate a AVL Tree and print out the preorder traversal result to help me validate whether that's different from a BST
## TreeNode.java
Defines TreeNode Class with attributes for value, left, right and height (we need that to determine whether rotation is needed)
## AVLTree.java
Containing methods to initialize an empty tree, and perform insertion, search, deletion, and in-order traversal. What's different from the BST assignment is, there's also helper method on rotation, and calculating height difference to determine whether rotation is needed.
## AVLTreeTest.java
Including testing methods to check whether methods in AVLTree.java are working as expected
