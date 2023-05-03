Download Link: https://assignmentchef.com/product/solved-cs-340-programming-assignment-vi-knapsack-via-dynamic-programming
<br>
<strong>CS 340 Programming Assignment VI:</strong>

<strong>Knapsack via Dynamic Programming</strong>

<strong>Description: </strong>You are to implement the O(nW) matrix based dynamic programming algorithm to solve the Knapsack problem.

<strong>I/O Specifications: </strong>You will read your input instance from an input file named <strong>knapsack.txt </strong>of the following format: The first line will specify the number of items n and the weight bound W.  Every following line k will specify the weight of item k and the value of item k (separated by a space).  A sample input corresponding to slide 28 is as follows:




4 6

2 4

<ul>

 <li>5</li>

 <li>1</li>

 <li>2</li>

</ul>




Output will give both the total value of the optimal Knapsack solution, and the subset of items involved in the optimal Knapsack solution.  Output will be to console.  E.g., the output for the example above is:




The optimal Knapsack solution has total value 11 and involves items {1, 2, 4}.




<strong>Algorithmic Specifications: </strong>The dynamic programming algorithm is exactly as described in the slides 13Dynamic programming.pptx and the Dynamic Programming chapter of the text.  It is based on constructing the n by W matrix of all optimal subproblems, where each enty (r,c) depends only on the entries (r-1,c) and (r-1,c-w<sub>r</sub>).  Including a “zeroth” row and “zeroth” column is also convenient, and those should be initialized to zero as well.  Observe that the overall time complexity of O(nW) is not actually polynomial time.


