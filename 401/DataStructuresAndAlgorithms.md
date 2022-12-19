# Data structures and Algorithms

> [Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)

*  Recursion makes the code look cleaner and easier to understand.

* Recursion has two parts:
  * Base Case - Function will stop calling itself.

  * Recursive Case - Function will call itself.

* Recursion has no performance increase.

> [Data Structures in 15 Minutes](https://www.youtube.com/watch?v=sVxBVvlnJsM)

* Big O notation - measure of how well an operation scales

* Linked list
  * Node - has a value and a pointer to the next node. 
  * Good at adding and deleting items. 
  * Bad at retrieval and searching.
* Array
  * A continuous block of cells in the computer memory. 
  * Good at retrieving an item
  * Bad at adding new items because it takes up a lot of memory
* Hash Table
  * Object in js or dictionary in Python
  * Uses key/value pair
  * Good at adding and removing
  * Bad because of key collisions
* Stack and Queue
  * Stack is first in last out
    * Add item from the top. You remove item from top.
  * Queue is first in, first out.
    * Add item to the end of the line. You take item in the front of the line. Think about getting into a club/bar.
* Graphs and Trees
  * Has nodes and edges
  * Tree - data flows in a one way. 
  * Binary Search Tree - can only have two children. Left or Right.

> [Big O Explained](https://www.youtube.com/watch?v=v4cd1O4zkGw)

* Big O
  * Algorithm Efficiency 
  * Constants get dropped
  * Different inputs need to be different variables
  * Drop non-dominate terms
* Analogy from the comments section of the video from Christine Hill to help better understand.

Let's say you're making dinner for your family. O is the process of following a recipe, and n is the number of times you follow a recipe.

O - you make one dish that everyone eats whether they like it or not. You follow one recipe from top to bottom, then serve (1 recipe). <-- How I grew up

O(n) - you make individual dishes for each person. You follow a recipe from top to bottom for each person in your family (recipe times the number of people in your family).

O(n^2) - you make individual dishes redundantly for every person. You follow all recipes for each person in your family (recipe times the number of people squared)... 

OR if every person in your family makes individual dish for every person (so every person will have n dishes) - this could be O(n^2)

O(log n) - you break people into groups according to what they want and make larger portions. You make one dish for each group (recipe times request)

> [Basic Data Structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

* 8 commonly used data structures
  * Arrays
  * Linked Lists
  * Stacks
  * Queues
  * Hash Tables
  * Trees
  * Heaps
  * Graphs

> ## Questions

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
  
* You should consider what kind of data you will be working with. Once you figure that out, you can plan on what kind of data structure to use and what be the most efficient way to use it

2. How can we ensure that we’ll avoid an infinite recursive call stack?

* Make sure you have a base case in the function.

> ### Other good reads
* [Why Big O](https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)

[Return Home](../README.md)
