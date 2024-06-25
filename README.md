# Binary Search Tree to Greater Sum Tree 

LeetCode Q # 1038.

Given the root of a Binary Search Tree (BST), convert it to a Greater Tree such that every key of the original BST is changed to the original key plus the sum of all keys greater than the original key in BST.

As a reminder, a binary search tree is a tree that satisfies these constraints:

- The left subtree of a node contains only nodes with keys less than the node's key.</br>
- The right subtree of a node contains only nodes with keys greater than the node's key.</br>
- Both the left and right subtrees must also be binary search trees.</br>

Example 1:

<div align="center">
  
  ![image](https://github.com/xo-azeem/Binary-Search-Tree-to-Greater-Sum-Tree-LeetCode/assets/171427226/ebb240f1-9aa5-4b98-9ed8-1cd9b1c9e30f)

</div>

> Input: root = [4,1,6,0,2,5,7,null,null,null,3,null,null,null,8]</br>
> Output: [30,36,21,36,35,26,15,null,null,null,33,null,null,null,8]

Example 2:

> Input: root = [0,null,1]</br>
> Output: [1,null,1]

My Solution Analysis:

<div align = "center" width="12" height="12">

  ![image](https://github.com/xo-azeem/Binary-Search-Tree-to-Greater-Sum-Tree-LeetCode/assets/171427226/80025d2c-5613-424e-abf3-0d64d4d96dd7)

  Time complexity: O(n).</br>Space complexity: O(n).
</div>
