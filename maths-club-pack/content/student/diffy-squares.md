---
title: Diffy Squares
type: problem
printOrder: 999
added: 2021-01
---

# Diffy Squares

Create a Diffy Square by following this process:

1. Draw a square and choose four numbers to place on each vertex.

2. Along each edge, write the positive difference of the numbers at the vertices that the edge connects. Join these four numbers up to form a new square.

3. Now repeat this process with the new square. Find the positive difference between each pair of numbers which share an edge, write these differences on the edge and connect up the new numbers.

4. At some point, you will reach a square with four zeros on the edges. At this point, you should stop.

5. That's it. You should now count the number of squares which you drew, not including the largest square on the outside. This is the *length* of the sequence of squares.

Here is an example, starting with the numbers 7, 15, 9 and 13:

<img src="../../images/diffy-squares-1.png" width="250">

We drew two smaller squares, so this sequence has length 2.

Try following this process with different starting numbers.

What is the longest sequence of squares that you can find?


Tip: For longer sequences, it may be easier to write your sequences as a column of numbers, where each row represents a square.

For our example of length 2, we could have written:

<img src="../../images/diffy-squares-2.png" width="200">
