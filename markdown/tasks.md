---
title: Tasks
...

All tasks will be submitted and graded on [Gradescope](https://www.gradescope.com/courses/797871).


# Exercises

Some exercises may require submitting to multiple gradescope assignments (e.g. if there is a programming component as well as a written component). The assignment instructions will make it clear when this is the case.

## Exercise 0

The objectives of this exercise are to: 

- Set up your Java environment
- Refresh our Java programming skills
- Gain experience implementing data structures from an ADT
- Use Java generics
- Use benchmarking to study the running time of algorithms

This assignment has two main parts. The first involves implementing some data structures. The second involves analyzing the running times of your implementations using benchmarking. Each part will have a separate Gradescope submission, which will combine together to count as your exercise 0 grade.

For this exercise, you will need:

- [Starter Code](/files/exercises/ex0.zip) - which contains various classes that will be needed for this assignment.
- [Specification](https://docs.google.com/document/d/1Tq_at8VAZOueWtMm6UWtNZmAhoKapmX7Woqp1xfIwiQ/edit?usp=sharing) - which contains all instructions for what to do for this assignment.
- [Benchmarking Worksheet](https://docs.google.com/document/d/1xKSboyCwlGAl4boIP_5TLEb1zCRIWoxvRJdCHFvga8I/edit?usp=sharing) - which you will copy and complete for the benchmarking portion of the assignment.

## Exercise 1

The objectives of this exercise are to:

- Gain experience identifying running times of given code
- Use the formal definitions of big-Oh, big-Omega, and big-Theta
- See examples of what changes to function do/don't change their asymptotic behavior

Instructions for this exercise are in Gradescope. To submit you will provide your answers there (either as a fill-in-the-blank or by uploading your work as an image or pdf).

Here are some [sample solutions for question 5](files/exercises/cse332_ex01_su24_solutions.pdf).

## Exercise 2

The objectives of this exercise are to:

- Gain experience with solving recurrence relations using the tree method
- See examples of how different changes to recurrence relations do/don't change their asymptotic behavior

Instructions for this exercise are in Gradescope. To submit you will provide your answers there (either as a fill-in-the-blank or by uploading your work as an image or pdf).

Here are some [sample solutions](files/exercises/exercise2_solutions.pdf).

## Exercise 3

The objectives of this exercise are to:

- Understand the binary heap data structure by implementing it
- See how to modify the binary heap data structure to add new operations efficiently
- Apply the binary heap data structure to create a new data structure

This is a programming exercise which you will submit to gradescope. There is no written component to this exercise, your code is your only submission. For this exercise, you will need:

- [Starter Code](/files/exercises/ex3.zip) - which contains various classes that will be needed for this assignment.
- [Specification](https://docs.google.com/document/d/1VdB7eXj89m6n0VUerDlfb39tAphi16aEzbhrQQMx4g0/edit?usp=sharing) - which contains all instructions for what to do for this assignment.

## Exercise 4

The objectives of this exercise are to:

- Identify the relationships between binary search trees and AVL trees by implementing AVL trees as a subclass of binary search trees (and thereby inheriting methods whenever possible).
- Develop familiarity with the AVLTree data structure by implementing it. In particular: understanding what information needs to be maintained in order to preserve the structure property (height of subtrees differs by 0 or 1), using that information to correctly identify to perform rotation operations.
- Highlight the advantages of using an ordered dictionary data structure (like a binary search tree) by using one to implement a new data structure


This is a programming exercise which you will submit to gradescope. There is no written component to this exercise, your code is your only submission. For this exercise, you will need:

- [Starter Code](/files/exercises/ex4.zip) - which contains various classes that will be needed for this assignment.
- [Specification](https://docs.google.com/document/d/1mjVqF-Qi_mJ4ze0XAn_Q64Cj9zNCG-bd_H3TXgtV3Jw/edit?usp=sharing) - which contains all instructions for what to do for this assignment.


## Exercise 5

The objectives of this exercise are: 

- Understand the mechanics of an efficient chaining hash table by implementing one of your own
- See how to write a good hash function for a new data structure
- Apply the advantages of a hash table by using it as part of an algorithm that involves a large number of inserts and finds of a large dictionary.


This is a programming exercise which you will submit to gradescope. There is no written component to this exercise, your code is your only submission. For this exercise, you will need:

- [Starter Code](/files/exercises/ex5.zip) - which contains various classes that will be needed for this assignment.
- [Specification](https://docs.google.com/document/d/1Vr_UM8oBhT7nja7n7XEq16d0dq3xseKF5pX9_jZaUa0/edit?usp=sharing) - which contains all instructions for what to do for this assignment.

## Exercise 6

The objectives of this exercise are:

- Recognize the need for various sorting algorithm properties in applications in order to select the best-fit algorithm
- Demonstrate how to determine whether or not an algorithm possess the property of being a stable sort
- Apply the insights utilized from studying sorting algorithms to develop a new algorithm 

Instructions for this exercise are in Gradescope. To submit you will provide your answers there (either as a fill-in-the-blank or by uploading your work as an image or pdf).

# Resubmissions

## Resubmission 1

For this resubmission you may resubmit any assignment which covered content through the midterm exam. This includes EX0, EX1, EX2, EX3, and EX4. To indicate which assignment you would like to resubmit, please fill out [this form](https://docs.google.com/forms/d/e/1FAIpQLSezOKB4d5Wmzi7ajoXrYkL8NGjoieqshK-xGqklqBuZOUcs3A/viewform?usp=sf_link). Please do so by Thursday, 7/25. 

If you choose to resubmit a programming exercise (EX0, EX3, EX4) then we will extend your deadline for that exercise until Monday 7/29. Written exercises (EX1, EX2) have different versions for the resubmission with slightly alterred questions. We will enable you to submit to these altered version if you choose to resubmit one of those exercises.

Resubmitting is completely optional. If you are satisfied with your current grades then you're welcome to ignore the resubmissions. If you choose to resubmit an assignment, the new submission's grade will replace the original, whether lower or higher.


# Exams

## Exam 1

The Midterm Exam will be held on Friday July 19 during our normal lecture session.

### Policies

1. Closed book, closed notes except for a 1-page 2-sided reference sheet of your own creation.
1. No calculators, cell phones, or other electronic devices allowed.
1. No writing after time is called, make sure you put your name on your paper first.
1. You will be provided a [reference sheet](files/midterm_reference.pdf) (tentative) during the exam.

### Content

The exam will cover all material from the beginning of the quarter up through AVL Trees. This includes:

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
- Trees:
	- Definitions of height, branching factor
	- Preorder, Inorder, Postorder traversals of binary trees
- Dictionaries:
	- ADT operations
	- Binary Search Trees: Definition, algorithms and running times of dictionary operations
	- AVL Trees: Definition, algorithms and running times of dictionary operations (including the definition of rotations and when to do them). The delete operation will NOT be covered.

### Past Exams

I have drafted a practice exam that is representative of this quarter's midterm: [24su practice midterm](files/cse332-midterm-24su-sample.pdf) and [Solution](files/cse332-midterm-24su-sample-soln.pdf)

Below I have several quarters' midterm exams. Be advised that the question style, length, difficulty, and content may differ among quarters. Most notably, prior quarters covered two data structures that have been omitted from the course this quarter - Tries and B-Trees. In lieue of those, the summer 2024 exam has a greater emphasis on running time content. 

Overall, here is how I would recommend that you use these sample exams to prepare. 

- First, study on your own without using any of the provided sample exams. To do this, review the exercises, lecture slides, and section materials. If there are things included in there that you do not recall or find confusing, look those up to seek clarification.
- Next, use the past exams below to evaluate your preparedness. Attempt some problems, then compare your answer against the solution provided. If they differ, try to diagnose whether you answer is equally valid, or else where you may have a misconception (you're welcome to come to office hours for help!). In other quarters the final exam was cumulative, so you will be able to find additional practice within the previous final exams as well. 
- Once you are confident with your ability to answer questions in the past exams, take the practice exam above as a simulation of the actual exam (so create your reference sheet and then set aside as 60 minute block of time to take the exam from start to finish). Then trade exams with a friend so that they can compare your solutions to the key above and give you feedback.
- Use this feedback to decide where to review.

Past Exams:

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
1. You will be provided a [reference sheet](files/cse332_final_wi24_reference.pdf) (tentative) during the exam.

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
		- Bucket Sort
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
		- Critical section size
		- Deadlock
- P, NP, NP-Completeness, EXP
	- Definitions and relationships between these classes. For example, questions like:
		- If a problem belongs to class NP, does it belong to P? How about EXP?
		- If I have a verification algorithm that runs in quadratic time, which classes does it belong to from P, NP, EXP?
	- Examples of problems in each

Note: You will likely be asked to write java code using ForkJoin and/or threads. We will not require your syntax to be perfectly correct, but it should be correct enough that we can verify the code's would be correct if syntax issues were fixed. That is, we expect edge cases and other considerations of an algorithm to be correct, but don't necessarily expect all keywords or semicolons to be perfect.

The final exam is not designed to be cumulative in that there may be questions designed to specifically test on content from the midterm. However, knowledge of all content from the midterm will be assumed, and so some questions may incidentally involve midterm material. For example, a question relating to sorting may involve evaluating the running time of code. A question involving graphs may require knowledge of trees.

### Past Exams

We have provided links to past exams below. Be advised that in other (non-summer) quarters the final exam has been cumulative, and so you will see content on these covered on the midterm. The final exam for this summer will not include midterm content, and can be best approximated by simply omitted those portions of the exams below. I recommend that you mostly use these exams to evaluate your preparedness rather than as a study guide.

- [CSE 332 23au](files/cse332-final-23au.pdf), [Solution](files/cse332-final-23au-soln.pdf)
- [CSE 332 23wi](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-23wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-23wi-soln.pdf)
- [CSE 332 19au](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19au-soln.pdf)
- [CSE 332 19wi](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-19wi-soln.pdf)
- [CSE 332 18au](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18au.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18au-soln.pdf)
- [CSE 332 18wi](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18wi.pdf), [Solution](https://courses.cs.washington.edu/courses/cse332/23sp/exams/oldExams/cse332-final-18wi-soln.pdf)

