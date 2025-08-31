# To Do

## Binary tree

The binary tree here will be Dr. Jonas' own implementation. May not be the traditional binary tree (to be seen). Some key charateristics are the `node` and the `leaf`, and behavior of tree traversing via the *left* side. The left side will be populated with nodes with leaves extending right and outwards. Nodes represent paths (like a filesystem folder), and the leaves representing the objects within the folder.

![binary_tree](./media/binary_tree_for_db.png "Binary Tree")


- [ ] Implement a node (`s_node`)
- [ ] Implement a leaf (`s_leaf`)
- [ ] Implement a `u_tree`
  - the `u_tree` (a union), will hold the definitions for both the structs of a node and a leaf, but never defines both at the same time (can only instantiate one or the other) (to save memory)

