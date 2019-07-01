# Awesome-Coding-Interview-Design-Patterns
# This repo contains the most common design-patterns of a coding interview


The following patterns assume that you’ve brushed up on Data Structures.
 Here is  the top 14 patterns that can be used to solve most of the coding interview questions.


# 1)Sliding Window
The Sliding Window pattern is used to perform a required operation on a specific window size of a given array or linked list, such as finding the longest subarray containing all 1s. Sliding Windows start from the 1st element and keep shifting right by one element and adjust the length of the window according to the problem that you are solving. In some cases, the window size remains constant and in other cases the sizes grows or shrinks.


Following are some ways you can identify that the given problem might require a sliding window:

- The problem input is a linear data structure such as a linked list, array, or string
- You’re asked to find the longest/shortest substring, subarray, or a desired value

Common problems you use the sliding window pattern with:

- Maximum sum subarray of size ‘K’ (easy)
- Longest substring with ‘K’ distinct characters (medium)
- String anagrams (hard)

# 2)2 Pointers or Iterators
Two Pointers is a pattern where two pointers iterate through the data structure in tandem until one or both of the pointers hit a certain condition. Two Pointers is often useful when searching pairs in a sorted array or linked list; for example, when you have to compare each element of an array to its other elements.

Two pointers are needed because with just pointer, you would have to continually loop back through the array to find the answer. This back and forth with a single iterator is inefficient for time and space complexity — a concept referred to as asymptotic analysis. While the brute force or naive solution with 1 pointer would work, it will produce something along the lines of O(n²). In many cases, two pointers can help you find a solution with better space or runtime complexity.


Ways to identify when to use the Two Pointer method:

- It will feature problems where you deal with sorted arrays (or Linked Lists) and need to find a set of elements that fulfill certain constraints
- The set of elements in the array is a pair, a triplet, or even a subarray

Here are some problems that feature the Two Pointer pattern:

- Squaring a sorted array (easy)
- Triplets that sum to zero (medium)
- Comparing strings that contain backspaces (medium)

# 3)Fast and Slow Pointers or Iterators
The Fast and Slow pointer approach, also known as the Hare & Tortoise algorithm, is a pointer algorithm that uses two pointers which move through the array (or sequence/linked list) at different speeds. This approach is quite useful when dealing with cyclic linked lists or arrays.

By moving at different speeds (say, in a cyclic linked list), the algorithm proves that the two pointers are bound to meet. The fast pointer should catch the slow pointer once both the pointers are in a cyclic loop.


How do you identify when to use the Fast and Slow pattern?

- The problem will deal with a loop in a linked list or array
- When you need to know the position of a certain element or the overall length of the linked list.

When should I use it over the Two Pointer method mentioned above?

- There are some cases where you shouldn’t use the Two Pointer approach such as in a singly linked list where you can’t move in a backwards direction. An example of when to use the Fast and Slow pattern is when you’re trying to determine if a linked list is a palindrome.

Problems featuring the fast and slow pointers pattern:

- Linked List Cycle (easy)
- Palindrome Linked List (medium)
- Cycle in a Circular Array (hard)

# 4)Merge Intervals
The Merge Intervals pattern is an efficient technique to deal with overlapping intervals. In a lot of problems involving intervals, you either need to find overlapping intervals or merge intervals if they overlap. The pattern works like this:

Given two intervals (‘a’ and ‘b’), there will be six different ways the two intervals can relate to each other:

Understanding and recognizing these six cases will help you help you solve a wide range of problems from inserting intervals to optimizing interval merges.

How do you identify when to use the Merge Intervals pattern?

- If you’re asked to produce a list with only mutually exclusive intervals
- If you hear the term “overlapping intervals”.

Merge interval problem patterns:

- Intervals Intersection (medium)
- Maximum CPU Load (hard)

# 5)Cyclic sort
This pattern describes an interesting approach to deal with problems involving arrays containing numbers in a given range. The Cyclic Sort pattern iterates over the array one number at a time, and if the current number you are iterating is not at the correct index, you swap it with the number at its correct index. You could try placing the number in its correct index, but this will produce a complexity of O(n^2) which is not optimal, hence the Cyclic Sort pattern.


How do I identify this pattern?

- They will be problems involving a sorted array with numbers in a given range
- If the problem asks you to find the missing/duplicate/smallest number in an sorted/rotated array

Problems featuring cyclic sort pattern:

- Find the Missing Number (easy)
- Find the Smallest Missing Positive Number (medium)

# 6)In-place reversal of linked list

# 7)Tree BFS

# 8)Tree DFS

# 9)Two heaps

# 10)Subsets

# 11)Modified binary search

# 12)Top K elements

# 13)K-way merge

# 14)Topological sort
