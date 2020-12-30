# 100 Days Of Code - Log

### Day 1: December 29, 2020, Tuesday

**Today's Progress**: Learned an algorithm on how to Invert a Binary Tree.

**Thoughts:** I really enjoyed formulating the algorithm on how to invert a Binary Tree. I did struggled on a slightly different problem to my binary tree (the insertion method of my BinaryTree class) where I'm having an infinite loop. I just found out that I haven't accounted for inserting an item that's already existing on the tree so I just decided to ignore these instances by returning None value and finally fixed the bug on the insert method of my BinaryTree class. But overall, my algorithm for inverting a binary tree works and I really enjoyed how I thought of formulating a solution to make a recursive function.

**Link to work:** [Data Structures and Algorithms](https://github.com/menard19/data-structures-and-algorithms/blob/main/data_structures.py)

### Day 2: December 30, 2020, Tuesday

**Today's Progress**: Learned Topological Sort.

**Thoughts:** Today, I learned about formulating an algorithm to do topological sort. Upon coding it, I realized how it relates similarly to depth first search, specifically post-order DFS where I noticed that topological sort is the same as inverting a post-order DFS. So I googled it and found an article by geeksforgeeks where they said that topological sort is indeed a reversed post-order DFS. And on my code, I used the deque class from collections module (this is in Python btw) so that I can append at the beginning and do not bother storing the data as list and returning the inverse of it. At the end, I enjoyed learning and coding top-sort as a fun little brain exercise.

**Link to work:** [Data Structures and Algorithms](https://github.com/menard19/data-structures-and-algorithms/blob/main/data_structures.py)
