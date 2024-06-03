---
title: Tasks
...

All tasks will be submitted and graded on [Gradescope](https://www.gradescope.com/courses/691776).

# Exercises


# Exams

## Exam 1

The Midterm Exam will be held on Friday July 19 during our normal lecture session.

### Policies

1. Closed book, closed notes except for a 1-page 2-sided reference sheet of your own creation.
1. No calculators, cell phones, or other electronic devices allowed.
1. No writing after time is called, make sure you put your name on your paper first.
1. You will be provided a [reference sheet](files/midterm_reference.pdf) during the exam.

### Content

The exam will cover all material from the beginning of the quarter up through B Trees. This includes:

- Abstract Data Types and Data structures:
	- Their Definitions and Differences
	- Examples
- Stacks and Queues:
	- Array and Linked List implementations and running times
	- ADT Operations
- Asymptotic Complexity:
	- Definition of big-oh, big-omega, big-theta
	- Identifying whether f(n) belongs to O(g(n)) (or big-omega, big-theta)
	- Finding constants c and n0 to demonstrate this
	- Identifying running times (best case and worst case) of example code
- Recurrence Relations:
	- Given a recurrence relation, solve it to closed form
- Priority Queues:
	- ADT operations (insert, findMin, deleteMin, increaseKey, decreaseKey, remove)
	- The Heap data structure (including the heap property, complete tree, and buildHeap)
- Tries:
	- Find, insert, and delete operations
- Trees:
	- Definitions of height, branching factor
	- Preorder, Inorder, Postorder traversals of binary trees
- Dictionaries:
	- ADT operations
	- Binary Search Trees: Definition, algorithms and running times of dictionary operations
	- AVL Trees: Definition, algorithms and running times of dictionary operations (including the definition of rotations and when to do them). The delete operation will NOT be covered.

### Past Exams

We have provided links to past exams below. Since all past exams were given by a different instructor, be advised that the question style, length, and difficulty may be different this quarter. I recommend that you mostly use these exams to evaluate your preparedness rather than as a study guide.

- [CSE 332 23au Midterm](files/cse332-midterm-23au.pdf), [Solution](files/cse332-midterm-23au-soln.pdf)
- [CSE 332 23sp Midterm](files/cse332-midterm-23sp.pdf), [Solution](files/cse332-midterm-23sp-soln.pdf)
- [CSE 332 23wi Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-23wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-23wi-soln.pdf)
- [CSE 332 22su Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-22su.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-22su-soln.pdf)
- [CSE 332 19au Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-19au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-19au-soln.pdf)
- [CSE 332 19wi Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-19wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-19wi-soln.pdf)
- [CSE 332 18au Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-18au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-18au-soln.pdf)
- [CSE 332 18wi Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-18wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-18wi-soln.pdf)
- [CSE 332 17au Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-17au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-17au-soln.pdf)
- [CSE 332 16au Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-16au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-16au-soln.pdf)
- [CSE 332 15wi Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-15wi-A.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-15wi-A-soln.pdf)
- [CSE 332 14sp Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-14sp.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-14sp-soln.pdf)
- [CSE 332 13au Midterm](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-13au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-midterm-13au-soln.pdf)

## Exam 2

The Final Exam will be held on Friday August 16 in lecture.

### Policies

1. Closed book, closed notes except for a 1-page 2-sided reference sheet of your own creation.
1. No calculators, cell phones, or other electronic devices allowed.
1. No writing after time is called, make sure you put your name on your paper first.
1. You will be provided a [reference sheet](files/cse332_final_wi24_reference.pdf) during the exam.

### Content

The final exam will cover:

- Hash Tables:
	- Principles of good hash function design
	- Insert/Delete/Find using these collision resolution strategies:
		- Separate Chaining
		- Linear Probing
		- Quadratic Probing
		- Double Hashing
	- Strengths and weaknesses of each collision resolution strategy
	- Load Factor, including how to calculate it and how it interacts with collision resolution
	- Rehashing
- Sorting
	- Definitions, procedures, running times, and other properties of these algorithms:
		- Selection Sort
		- Insertion Sort
		- Heap Sort
		- Merge Sort
		- Quick Sort
		- Buckeet Sort
		- Radix Sort
- Graphs
	- The definitions of the many terms presented in the graphs section, including: 
		- node/vertex
		- edge, edge weight
		- directed/undirected graph
		- (in/out) degree
		- complete graph
		- simple graph
		- path, simple path, and cycle
		- connected graph
		- DAG
		- tree
		- Any other definitions presented in the slides
	- Graph data structures (adjacency list, adjacency matrix) and the advantages and disadvantages of each.
	- Graph Traversals (breadth-first search and depth-first search)
	- Dijkstra's Algorithm
	- Prim's algorithm and Kruskal's Algorithm
	- Topological Sort
- Parallelism:
	- ForkJoin Parallelism
	- Efficiency analysis (including work, span, perfect linear speedup, and Amdahl's Law)
	- ForkJoin applications:
		- Reduce: Parallel sum, max, find, etc.
		- Map: vector addition, function application, etc.
	- Parallel Prefix Sum
	- Parallel Filter
- Concurrency
	- Race Conditions:
		- Data Races
		- Bad Interleavings
	- Code Synchronization:
		- Locks, reentrant locks
		- Java's Synchronized statement
		- Lock scheme granularity (coarse vs. fine)
		- Criticl section size
		- Deadlock
- P, NP, NP-Completeness, EXP
	- Definitions and relationships between these classes. For example, questions like:
		- If a problem belongs to class NP, does it belong to P? How about EXP?
		- If I have a verification algorithm that runs in quadratic time, which classes does it belong to from P, NP, EXP?
	- Examples of problems in each

Note: You will likely be asked to write java code using ForkJoin and/or threads. We will not require your syntax to be perfectly correct, but it should be correct enough that we can verify the code's would be correct if syntax issues were fixed. That is, we expect edge cases and other considerations of an algorithm to be correct, but don't necessarily expect all keywords or semicolons to be perfect.

### Past Exams

We have provided links to past exams below. Since all past exams were given by a different instructor, be advised that the question style, length, and difficulty may be different this quarter. I recommend that you mostly use these exams to evaluate your preparedness rather than as a study guide. In summary, question style will be similar to the midterm, quest content will be similar to the exams below.

- [CSE 332 23au](files/cse332-final-23au.pdf), [Solution](files/cse332-final-23au-soln.pdf)
- [CSE 332 23wi](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-23wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-23wi-soln.pdf)
- [CSE 332 19au](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19au-soln.pdf)
- [CSE 332 19wi](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19wi-soln.pdf)
- [CSE 332 18au](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18au-soln.pdf)
- [CSE 332 18wi](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18wi-soln.pdf)

