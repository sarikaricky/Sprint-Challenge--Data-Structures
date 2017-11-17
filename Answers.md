1. What are the order of insertions/removals for the following data structures?  A stack is referred to as a last-in-first-out (LIFO) structure, meaning that the most recently added item is the first one removed. A stack is a last-in-first-out (LIFO) structure while a queue is a first-in-first-out (FIFO) structure.
   - **Stack**
   - **Queue**
2. What is the retreival time complexity for the following data structures?
   - **Linked List**--LinkedList get(int index) operation run time is O(n) .
   - **Hash Table**-- All hash table implementations offer O(1) on the vast, vast, vast majority of inserts. This is the same as array inserting - it's O(1) unless you need to resize, in which case it's O(n), plus the collision uncertainty.
   - **Binary Search Trees**-- Since a Binary Tree is also a Graph, the same applies here. The complexity of each of these Depth-first traversals is O(n+m).
2. What are some advantages to using a Hash Tables over an array in JavaScript? In Javascript, we can create our own classes. So what we are going to do is create a HashTable() class that can maintain an associative array, but isolate API methods from data keys (no conflicts).

## Challenge
If you take a look at the hash-table.js file you'll notice that it has solution code in it. You'll also notice that if you run the tests, they all pass. Your job is to refactor this hash table solution to use **linked lists** for buckets instead of arrays. You're welcome to add another class to the helper file, following the pattern used with LimitedArray.