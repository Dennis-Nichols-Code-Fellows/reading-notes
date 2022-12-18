# Code 401 - Data Structures and Algorithms Prep

## Basic Recursion Video

- Recursion is a building block for use with later DSA topics
- It's useful for dealing with nested data structures
- We should use recursion when it makes the solution more clear
- There's no performance benefit to recursion and may even be a penalty compared to loops BUT it sometimes makes code much more easy to understand.
- Recursive functions need to include a *base case* which tells the function when to stop

## Data structures in 15 minutes video

**What is a data structure?**
The manner in which we store related data items.

5 most important data structures:

- Linked list
  - Contains nodes: each node has a value and a next node pointer
  - it's good at adding items but not at retrieving items

- Array
  - Sequential block of memory locations
  - Great for retrieving items
  - Adding is less efficient because you might have to move the array as it gets to large

- Hash table
  - Known as an object in JS, dict in Python
  - Key:value pairs
  - The key gets converted to a memory by a hashing function
  - it's possible for 2 keys to be assigned the same memory location by the hashing function -> called a *collision*

- Stacks and Queues
  - Stack is a LIFO data structure
    - you push things onto the stack and then pop them off
    - used in depth-first search
  - A queue is a FIFO data structure
    - You add to the end, but remove from the beginning
    - used in breadth-first search

- Graphs and Trees
  - Has nodes and edges
  - The connections between nodes are the edges.
  - Edges can have weights assigned to them
  - A tree is a graph that only goes in one direction

## Big O video

- How time scales (to run and algo) with respect to input variables
- You need to know what is most clear for describing your runtime

Rules for describing Big O

- If you have different steps in an algo, you add those steps
- You drop constants
- If you have different inputs, you describe them separately
- Drop non-dominant terms

## Data structures reading

**8 most important DS**

Have mostly been described in the DS video notes so I'll just put new things in here.

1. Arrays

- Used as building blocks of other DS
- Used for sorting algorithms

2. Linked Lists

- Used for symbol table management in compiler design

3. Stacks

- Used for expression evaluation
- Used to implement function calls in recursive programming

4. Queues

- Used to manage threads in multi-threading
- Used to implement priority queues

5. Hash tables

- Used to implement DB indexes, associative arrays, the set DS

6. Trees

- Binary trees used to implement expresssion solvers
- Binary search trees used in many search algorithms

7. Heaps

- These are a special case of binary tree.
- They are trees where parent nodes are structured in relation to the values of their children.
- Used to more efficiently implement queuing functions
- Used to find the kth smallest/largest value in a given array

8. Graphs

- Directed graphs - edges have a direction indicating start and end vertices
- Undirected graphs are what they sound like
- Graphs are used to implement networks, links between web pages, locations and routes in GPS, etc.


## Why Big O - article

- It's good to learn Big O because designing efficient algorithms is the whole point of much of computer science and programming.
- Big O puts algorithms in context and thus can aid in learning them.
- Big O helps avoid mistakes in implementation of algorithms.

## Things I want to know more about:

- Graphs and trees seem so interesting and important.
