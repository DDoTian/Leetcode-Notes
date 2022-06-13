# Binary Tree

![[Binary Tree huahua.PNG]]

1.  Tree 存在heap上，无序，访问时用stack
2.  Binary Search Tree: vals of left-subtrees <= root.val <= vals of right-subtrees (no need to be balanced)
3.  Balanced Tree: the height different of left/right sub-trees is at most 1
4.  Tree Traversal: 前、中、后续(pre/in/post order); for a BST, 中续(inorder)-> sorted
5.  think about the problem in a recursive way -> what to return -> when to return
![[Binary Tree huahua-find max of a tree.PNG]]
6. Template 1: one root ![[Binary Tree huahua-template 1.PNG]]
7. Template 2: two roots ![[Binary Tree huahua-template 2.PNG]]