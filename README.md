![download](https://user-images.githubusercontent.com/111001224/222364731-2ecd49fa-472c-40a5-8d45-1bd335983de7.png)


# 0x1D. C - Binary trees

##	Requirements

##	General

- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- You are allowed to use the standard library
- In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called binary_trees.h
- Don’t forget to push your header file
- All your header files should be include guarded

## Tasks :page_with_curl:

* **0. New node**
  * [0-binary_tree_node.c](./0-binary_tree_node.c): C function that creates a
  binary tree node with a given parent and value.
  * Returns a pointer to the new node, or `NULL` on failure.

* **1. Insert left**
  * [1-binary_tree_insert](./1-binary_tree_insert): C function that inserts a
  node as the left-child of another.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the given `parent` already contains a left node, the new node takes its
  place and the old left-child becomes the left-child of the new node.

* **2. Insert right**
  * [2-binary_tree_insert_right.c](./2-binary_tree_insert_right.c): C function that
  inserts a node as the right-child of another.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the given `parent` already contains a right node, the new node takes its
  place and the old right-child becomes the right-child of the new node.

* **3. Delete**
  * [3-binary_tree_delete.c](./3-binary_tree_delete.c): C function that deletes
  an entire binary tree.

* **4. Is leaf**
  * [4-binary_tree_is_leaf.c](./4-binary_tree_is_leaf.c): C function that checks
  if a given node is a leaf.
  * Returns `1` if the node is a leaf, `0` otherwise.

* **5. Is root**
  * [5-binary_tree_is_root.c](./5-binary_tree_is_root.c): C function that checks
  if a given node is a root.
  * Returns `1` if the node is a root, `0` otherwise.

* **6. Pre-order traversal**
  * [6-binary_tree_preorder.c](./6-binary_tree_preorder.c): C function that
  traverses a tree using pre-order traversal.

* **7. In-order traversal**
  * [7-binary_tree_inorder.c](./7-binary_tree_inorder.c): C function that
  traverses a tree using in-order traversal.

* **8. Post-order traversal**
  * [8-binary_tree_postorder.c](./8-binary_tree_postorder.c): C function that
  traverses a tree using post-order traversal.

* **9. Height**
  * [9-binary_tree_height.c](./9-binary_tree_height.c): C function that returns
  the height of a binary tree.

* **10. Depth**
  * [10-binary_tree_depth.c](./10-binary_tree_depth.c): C function that returns
  the depth of a given node in a binary tree.

* **11. Size**
  * [11-binary_tree_size.c](./11-binary_tree_size.c): C function that returns
  the size of a binary tree.

* **12. Leaves**
  * [12-binary_tree_leaves.c](./12-binary_tree_leaves.c): C function that returns
  the number of leaves in a binary tree.

* **13. Nodes**
  * [13-binary_tree_nodes.c](./13-binary_tree_nodes.c): C function that returns
  the number of nodes in a binary tree with at least one child.

* **14. Balance factor**
  * [14-binary_tree_balance.c](./14-binary_tree_balance.c): C function that
  returns the balance factor of a binary tree.

* **15. Is full**
  * [15-binary_tree_is_full.c](./15-binary_tree_is_full.c): C function that
  checks if a binary tree is full.
  * Returns `1` if a tree is full, `0` otherwise.

* **16. Is perfect**
  * [16-binary_tree_is_perfect.c](./16-binary_tree_is_perfect.c): C function
  that checks if a binary tree is perfect.
  * Returns `1` if a tree is perfect, `0` otherwise.

* **17. Sibling**
  * [17-binary_tree_sibling.c](./17-binary_tree_sibling.c): C function that
  returns a pointer to the sibling of a given node in a binary tree.
  * Returns `NULL` if no sibling is found.

* **18. Uncle**
  * [18-binary_tree_uncle.c](./18-binary_tree_uncle.c): C function that
  returns a pointer to the uncle of a given node in a binary tree.
  * Returns `NULL` if no uncle is found.

* **19. Lowest common ancestor**
  * [100-binary_trees_ancestor.c](./100-binary_trees_ancestor.c): C function
  that returns a pointer to the lowest common ancestor node of two given nodes
  in a binary tree.
  * Returns `NULL` if no common ancestor is found.

* **20. Level-order traversal**
  * [101-binary_tree_levelorder.c](./101-binary_tree_levelorder.c): C function
  that traverses a binary tree using level-order traversal.

* **21. Is complete**
  * [102-binary_tree_is_complete.c](./102-binary_tree_is_complete.c): C function
  that checks if a binary tree is complete.
  * Returns `1` if the tree is complete, `0` otherwise.

* **22. Rotate left**
  * [103-binary_tree_rotate_left.c](./103-binary_tree_rotate_left.c): C function
  that performs a left-rotation on a binary tree.
  * Returns a pointer to the new root node of the tree after rotation.

* **23. Rotate right**
  * [104-binary_tree_rotate_right.c](./104-binary_tree_rotate_right.c): C function
  that performs a right-rotation on a binary tree.
  * Returns a pointer to the new root node of the tree after rotation.

* **24. Is BST**
  * [110-binary_tree_is_bst.c](./110-binary_tree_is_bst.c): C function that
  checks if a binary tree is a valid binary search tree.
  * Returns `1` if the tree is a valid BST, `0` otherwise.

* **25. BST - Insert**
  * [111-bst_insert.c](./111-bst_insert.c): C function that inserts a value into
  a binary search tree.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the tree is `NULL`, the value becomes the root node.
  * The value is ignored if it is already present in the tree.

* **26. BST - Array to BST**
  * [112-array_to_bst.c](./112-array_to_bst.c): C function that builds a binary
  search tree from an array.
  * Returns a pointer to the root node of the created tree, or `NULL` on failure.

* **27. BST - Search**
  * [113-bst_search.c](./113-bst_search.c): C function that searches for a value
  in a binary search tree.
  * If the value is matched in the BST, returns a pointer to the matched node.
  * Otherwise, returns `NULL`.

* **28. BST - Remove**
  * [114-bst_remove.c](./114-bst_remove.c): C function that removes a node from
  a binary search tree.
  * Returns a pointer to the new root node of the tree after deletion.
  * If the node to be deleted has two children, it is replaced with its first
  in-order successor.

* **29. Big O #BST**
  * [115-O](./115-O): Text file containing the average time complexities of
  binary search tree operations (one answer per line):
    * Inserting the value `n`.
    * Removing the node with the value `n`.
    * Searching for a node in a BST of size `n`.

* **30. Is AVL**
  * [120-binary_tree_is_avl.c](./120-binary_tree_is_avl.c): C function that checks if
  a binary tree is a valid AVL tree.
  * If the tree is a valid AVL tree, returns `1`.
  * Otherwise, returns `0`.

* **31. AVL - Insert**
  * [121-avl_insert.c](./121-avl_insert.c): C function that inserts a value in an AVL tree.
  * Returns a value to the inserted node, or `NULL` on failure.

* **32. AVL - Array to AVL**
  * [122-array_to_avl.c](./122-array_to_avl.c): C function that builds an AVL tree
  from an array.
  * Returns a pointer to the root node of the created AVL tree, or `NULL` on failure.
  * Ignores duplicate values.

* **35. Big O #AVL Tree**
  * [125-O](./125-O): Text file containing the average time complexities of AVL tree
  opeartions (one answer per line):
    * Inserting the value `n`.
    * Removing the node with the value `n`.
    * Searching for a node in an AVL tree of size `n`.

* **41. Big O #Binary Heap**
  * [135-O](./135-O): Text file containing the average time complexities of
  binary heap opeartions (one answer per line):
    * Inserting the value `n`.
    * Extracting the root node.
    * Searching for a node in a binary heap of size `n`.



### Author

Olayemi Obafuwa
obafuwaolayemi@gmail.com
