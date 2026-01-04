# DSA basic 

### INDEX
- [roadmap](#roadmap)
- [checklist](#checklist)
- [Programming Language](https://github.com/Saujanya-rajvanshi/C-)
- [OOPs basic](https://github.com/Saujanya-rajvanshi/THEORY)
- [dsa definition and types](#definition-and-types)
- [basic data structure](#basic-data-structure)

### roadmap
https://roadmap.sh/datastructures-and-algorithms?fl=0

### checklist 
Perfect, this is a **DSA roadmap image**, so I’ll convert it into a **clean GitHub-style checklist** ✅
Since **GitHub Markdown can’t actually color boxes**, the **best practice** is to use **🔵 blue circle emojis** to visually represent *blue boxes*.

You can **directly paste this into your README.md**.

---

# 🔵 DSA ROADMAP – CHECKLIST

## 🔵 Programming Fundamentals

* [ ] Pick a Language

  * [ ] C++

* [ ] Language Syntax

* [ ] Control Structures

* [ ] Pseudo Code

* [ ] Functions

* [ ] OOP Basics

---

## 🔵 Data Structures Basics

* [ ] What are Data Structures?
* [ ] Why are Data Structures Important?

### 🔹 Basic Data Structures

* [ ] Array
* [ ] Linked List
* [ ] Stack
* [ ] Queue
* [ ] Hash Table

---

## 🔵 Algorithmic Complexity

* [ ] Time vs Space Complexity
* [ ] How to Calculate Complexity?

### 🔹 Asymptotic Notation

* [ ] Big-O
* [ ] Big-Ω
* [ ] Big-Θ

### 🔹 Common Runtimes

* [ ] Constant
* [ ] Logarithmic
* [ ] Linear
* [ ] Polynomial
* [ ] Exponential
* [ ] Factorial

---

## 🔵 Searching Algorithms

* [ ] Linear Search
* [ ] Binary Search

---

## 🔵 Sorting Algorithms

* [ ] Bubble Sort
* [ ] Selection Sort
* [ ] Insertion Sort
* [ ] Merge Sort
* [ ] Quick Sort
* [ ] Heap Sort

---

## 🔵 Tree Data Structures

* [ ] Binary Tree
* [ ] Binary Search Tree
* [ ] AVL Tree
* [ ] B-Tree
* [ ] Heap

### 🔹 Tree Traversals

* [ ] Inorder
* [ ] Preorder
* [ ] Postorder

### 🔹 Tree Search

* [ ] Breadth First Search (BFS)
* [ ] Depth First Search (DFS)

---

## 🔵 Graph Data Structures

* [ ] Directed Graph
* [ ] Undirected Graph

### 🔹 Graph Traversals

* [ ] BFS
* [ ] DFS

### 🔹 Shortest Path Algorithms

* [ ] Dijkstra’s Algorithm
* [ ] Bellman-Ford Algorithm
* [ ] A* Algorithm

### 🔹 Minimum Spanning Tree

* [ ] Prim’s Algorithm
* [ ] Kruskal’s Algorithm

---

## 🔵 Advanced Data Structures

* [ ] Trie
* [ ] Segment Tree
* [ ] Fenwick Tree (BIT)
* [ ] Disjoint Set (Union-Find)
* [ ] Suffix Array / Suffix Tree

---

## 🔵 Complex Data Structures

* [ ] 2–3 Trees
* [ ] B / B+ Trees
* [ ] Skip List
* [ ] ISAM

---

## 🔵 Indexing

* [ ] Linear Indexing
* [ ] Tree-Based Indexing

---

## 🔵 Problem Solving Techniques

* [ ] Brute Force
* [ ] Backtracking
* [ ] Greedy Algorithms
* [ ] Randomized Algorithms
* [ ] Divide and Conquer
* [ ] Recursion
* [ ] Dynamic Programming
* [ ] Two Pointer Technique
* [ ] Sliding Window Technique

### 🔹 Pattern-Based Problems

* [ ] Island Traversal
* [ ] Merge Intervals
* [ ] Two Heaps
* [ ] Kth Element
* [ ] Cyclic Sort
* [ ] Fast & Slow Pointers
* [ ] Multi-threaded Problems

---

## 🔵 Platforms to Practice

* [ ] LeetCode
* [ ] Edabit

---

## definition and types

Data structures are specialized formats for organizing and storing data in a computer so that it can be used efficiently. They provide a means to manage large amounts of data efficiently for uses such as large databases and internet indexing services. They are critical to programming and are used in almost all software systems including web development, operating systems, image editing, and much more. Some common types of data structures are arrays, linked lists, queues, stacks, trees, and graphs. The choice of the data structure often begins from the choice of an abstract data type, a broad type encapsulating various possible data structures."

```cpp
                      Data Structure Types
                              |
              ---------------------------------------------
              |                                            |
     Primitive Data Structure                 Non-Primitive Data Structure
              |                                            |
   --------------------------------          --------------------------------------------------------------------
   |        |        |        |              |                             |                                 |
 Integer   Float  Character   pointer      Linear DS                   Non-Linear DS                      hashing
                                              |                             |                                |
                                   -------------------          --------------------------            ----------------
                                   |    |      |     |          |     |     |     |      |            |       |      |    
                                 Array Linked Stack Queue    Tree  Heap   Trie Graph   Hash         hash     hash   hash  
                                       List                                                         set      map    table
```

---

## 🔷 Linear vs Non-Linear Data Structures (Interview Table)

| **Aspect**                    | **Linear Data Structures**                                            | **Non-Linear Data Structures**                          |
| ----------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------- |
| **Definition**                | Data elements are arranged sequentially, one after another            | Data elements are arranged hierarchically or graph-like |
| **Data Relationship**         | Each element has a **single predecessor and successor** (except ends) | An element can have **multiple relationships**          |
| **Traversal**                 | Traversed in a **single run** (one direction)                         | Traversed in **multiple ways** (DFS, BFS, etc.)         |
| **Storage Order**             | Stored in **contiguous or logical sequence**                          | Stored in **non-sequential manner**                     |
| **Memory Utilization**        | Simpler memory usage                                                  | More complex memory management                          |
| **Complexity of Structure**   | Easy to implement and understand                                      | More complex to implement                               |
| **Data Access**               | Sequential access                                                     | Non-sequential access                                   |
| **Search Efficiency**         | Slower for large data sets                                            | Faster for complex relationships                        |
| **Insertion / Deletion**      | Costly (especially arrays)                                            | Efficient with proper structure                         |
| **Scalability**               | Less scalable                                                         | Highly scalable                                         |
| **Data Representation**       | Simple list-like structure                                            | Tree or network-like structure                          |
| **Real-World Mapping**        | Suitable for simple data flow                                         | Suitable for real-world hierarchical data               |
| **Performance**               | Efficient for small datasets                                          | Efficient for large and complex datasets                |
| **Implementation Difficulty** | Low                                                                   | Medium to High                                          |
| **Use Cases**                 | Simple applications                                                   | Complex applications                                    |
| **Examples**                  | Array, Stack, Queue, Linked List                                      | Tree, Graph, Heap, Trie, Hash Table                     |

---

## 🔹 Key Interview Insight (Google-Style)

**Linear DS** → best for **simple, sequential problems**
**Non-Linear DS** → best for **complex relationships & optimized search**

---

## 🔹 One-Line Interview Answer

> Linear data structures store data sequentially, while non-linear data structures organize data hierarchically or graph-based to represent complex relationships.

---

## ⭐ Pro Interview Tip

Interviewers often follow up with:

* ❓ *Why is a tree faster than an array for searching?*
* ❓ *When would you choose a graph over a tree?*

---

## 🔹 Importance of Data Structures

* Organize and store data efficiently
* Foundation of algorithm design
* Improve program performance
* Enable fast data access, insertion, and deletion
* Help in sorting, searching, and ordering data
* Reduce code complexity
* Make programs scalable and flexible
* Essential for software and database development

---

## basic data structure

#### array 
- [array repository](https://github.com/Saujanya-rajvanshi/Arrays-)

#### list 

#### stack 

#### queue

#### tree

#### graph

