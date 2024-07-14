# B Trees

**B-Trees** are a special type of self-balancing search tree in which each node can contain more than one key and can have more than two children. It is a generalized form of the [binary search tree](https://www.programiz.com/dsa/binary-search-tree).

It is also known as a height-balanced m-way tree.

![image](https://github.com/user-attachments/assets/6b0cf329-fe86-4c66-9c57-3b3bd786b462)

## Read Efficiency

The need for B-Tree arose with the rise in the need for less physical storage access time, especially in secondary storage devices where they have larger capacity but slower read speeds. There was a need for such types of data structures that minimize the disk access.

Other data structures such as a binary search tree, AVL tree, Eed-black tree, etc can store only one key in one node. As the number of keys needed increases, then the height of such trees becomes very large, and the access time increases.

However, B-tree can store many keys in a single node and can have multiple child nodes. This decreases the height significantly allowing faster disk accesses.

## Application: Databases

B-Trees are the main data structure used in SQL Databases for indexing. The B-tree index stores data in sorted order, which makes it very efficient for range queries and equality checks. 

## Presentation Slides and Code

You may view the prsentation slides and implementation code by clicking each of the links provided:

1. **[Part 1 - Concepts, Search, and Insertion](https://github.com/20100215/B_Tree_Implementation/blob/main/01_BTree_Concepts%2BSearch%2BInsert.ppsx)**
2. **[Part 2 - Deletion and Streamline Code Simulation](https://github.com/20100215/B_Tree_Implementation/blob/main/02_BTree_Delete%2BStreamlineCode.ppsx)** 
3. **[C Source Code](https://github.com/20100215/B_Tree_Implementation/blob/main/00_BTree-LinkedList-AllOperations.c)**

## Video Resource

Apart from the presentation slides and code in this repository, you may use this **[reference video by Spanning Tree](https://www.youtube.com/watch?v=K1a2Bk8NrYQ)** to supplement your understanding of the B-Tree operations.

---

Prepared by: [Wayne Dayata](https://github.com/20100215/), [Ivan Woogue](https://github.com/OG-Habit/), [Hannah Labana](https://github.com/hannahlabana), [Marc Valeros](https://github.com/marcvaleros)

CS 3102N Algorithms and Complexity 2022
