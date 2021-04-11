# Computational Geometry
Anmol Saraf

## CHECKPOINT 1

### Text 1 :-  _Introduction To Graph Theory by Robin J. Wilson_

### Concepts Learned :-

&nbsp; &nbsp; &nbsp; Basic Definitions and examples of graphs, how they are connected and visually represented. Also how to represent graphs in different types of matrices to store the graph in a more concise manner. Three graph problems namely **The eight circle problem, Six people at a party** and **The four cubes problem.**

**Eulerian** graphs, which are graphs such that all the edges are used to construct a closed trail such that all the edges are traversed once only. Similarly **Semi-Eulerian** graphs are where the once traversing of an edge rule is neglected.

**Hamiltonian** Graphs are the one in which a closed trail can be constructed such that it contains every vertex just once. Thus, **Semi-Hamiltonian** Graphs  allows vertices to be used more than once.

Common problems solved through the concept of Eulerian and Hamiltonian graphs such as **The shortest path problem, The chinese postman problem** and 	**The travelling salesman problem.**

**Trees** and **Forests** types of graphs and the proof of the total number of labelled trees of n vertices being n<sup>n-2</sup>. Furthermore the application of these tree graphs to enumerate the number of alkanes that can be formed from the formula of **C**<sub>n</sub>**H**<sub>2n+2</sub> shows the application of these types of graphs.

Problems using the theory of tree graphs such as The minimum connector problem, solved using a type of algorithm called the greedy algorithm, Electrical circuits and Searching Trees, using breadth- first search and depth-first search methods.

### Text 2 :- _The Design and Analysis of Computer Algorithms by Alfred V. Aho, John E. Hopcraft and Jeffrey &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; D. Ullman_

### Concepts Learned :- 

&nbsp; &nbsp; &nbsp; **Time** and **Space complexity** of an algorithm and how to calculate it. Getting better or faster computers will amount to less of a change to the time complexity of the algorithm than changing the algorithm to work better. A Basic model of **Random Access Machines**(RAM), what they are allowed to do and what is the time complexity for each operation they perform.

Use of **lists, queues** and **stacks** and which to use where to design efficient algorithms. Set representation using lists and **bit-vector representation** which has a great time advantage over using lists for sets, i.e., the time required being independent of the number of elements in the set in the former.

Some basic definitions and facts related to graphs and how to represent adjacency matrices and make adjacency lists for the graphs. Trees, maily binary trees and their representation in two arrays. 

### Text 3 :- _Computational Geometry by David M. Mount_

### Concepts Learned :- 

&nbsp; &nbsp; &nbsp; Basic introduction to Computational Geometry, what it comprises of, what its capable of and its limitations. **Fixed Radius near Neighbour problem** and how to solve it using bucketing in 1D which can then be expanded to higher dimensions. Basics of Geometry including **Affine** and **Euclidian** geometry. Convex Hulls, their orientations and the **Convex Hull problem**.

**Graham's Scan** method to find the outer hull which results in a time of O(nlog(n)). This uses stack to find if any point is not left outside, i.e., checks the concavity of the hull. Another algorithm to solve the convex hull method is the **Divide and Conquer** method which is that if we have two smaller hulls we can simply combine them to get the final answer. Thus, by dividing the number of points into smaller sets we get the answer recursively.

Another famous method is the **Quick Hull** method in which firstly a rectangle constructed by the extremities of the x and y co-ordinates of the points. Further is expanded along each edge to add the points left outside the polygon and simultaneously deleting the internal points.

### Websites Used for Some Concepts

1. **Graham's Scan :-** https://www.geeksforgeeks.org/convex-hull-set-2-graham-scan/
2. **Divide and Conquer :-** https://www.geeksforgeeks.org/convex-hull-using-divide-and-conquer-algorithm/
3. **Hashing :-** https://searchsqlserver.techtarget.com/definition/hashing#:~:text=Hashing%20is%20the%20transformation%20of,it%20using%20the%20original%20value

