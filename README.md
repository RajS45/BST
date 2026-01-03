# BST
Binary Search Tree

🌳 Binary Search Tree (BST) Basics
- A BST is a type of binary tree.
- For every node:
- All values in the left subtree are smaller than the node’s value.
- All values in the right subtree are larger than the node’s value.
- Usually, duplicates are not allowed.

⚡ Key Points
- Searching: You start at the root and move left or right depending on whether the target is smaller or larger. This makes searching fast when the tree is balanced.
- Insertion: You place the new value in the correct position by following the same left/right rule.
- Deletion: Three cases:
- Node is a leaf → just remove it.
- Node has one child → replace it with its child.
- Node has two children → replace it with its inorder successor (smallest in right subtree) or inorder predecessor (largest in left subtree).
- Traversal: Inorder traversal of a BST always gives a sorted list of values.

🧠 Why BST is useful
- Keeps data sorted automatically.
- Searching, inserting, and deleting can be done in O(log n) time if the tree is balanced.
- If the tree becomes skewed (like a linked list), operations degrade to O(n).

📘 Example
Imagine inserting numbers in this order: 8, 3, 10, 1, 6, 14, 4, 7, 13.
The BST looks like:

        8
       / \
      3   10
     / \     \
    1   6     14
       / \    /
      4   7  13


- Left of 8 are smaller numbers.
- Right of 8 are larger numbers.
- Inorder traversal → 1, 3, 4, 6, 7, 8, 10, 13, 14 (sorted).



