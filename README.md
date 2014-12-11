08_Graph_Lab
============

Implement a simple graph class

Requirements
------------

1. Implement all methods of the `Graph` class.

Reading
=======
"Open Data Structures," Chapter 12, the whole chapter. http://opendatastructures.org/ods-cpp/12_Graphs.html

Questions
=========

#### 1. Which of the above requirements work, and which do not? For each requirement, write a brief response.

1. add - Works, if the cost and nodes are in the correct range, then it will do it.
2. remove - Works, correctly removes it if it is found.
3. getCost - Works, returns the cost correctly between node1 and node2.

#### 2. For each of your methods, what is the worst-case running time? You may write your answer in terms of `n` (the number of vertices), `m` (the number of edges), `d` (the maximum degree of any node in the graph), or any combination of these. Try to give the most informative bound that you can.

1. add - O(d)
2. remove - O(m+d) I believe.
3. getCost - O(d)

TODO

#### 3. Exercise 12.1 from http://opendatastructures.org/ods-cpp/12_4_Discussion_Exercises.html. You may want to draw by hand, upload the picture online (Instagram, Twitter, imgur, or some place like that), and then just put a link here.
		http://imgur.com/p3irf08

#### 4. What is one question that confused you about this exercise, or one piece of advice you would share with students next semester?

		My advice is to read about the vector class to help you understand what's going on.