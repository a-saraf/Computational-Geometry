# Computational Geometry
Anmol Saraf

## CHECKPOINT 1 (25th March - 11th April)

### Text 1 :-  _Introduction To Graph Theory by Robin J. Wilson_

### Concepts Learned :-

&nbsp; &nbsp; &nbsp; Basic Definitions and examples of graphs, how they are connected and visually represented. Also how to represent graphs in different types of matrices to store the graph in a more concise manner. Three graph problems namely **The eight circle problem, Six people at a party** and **The four cubes problem.**

**Eulerian** graphs, which are graphs such that all the edges are used to construct a closed trail such that all the edges are traversed once only. Similarly **Semi-Eulerian** graphs are where the once traversing of an edge rule is neglected.

**Hamiltonian** Graphs are the one in which a closed trail can be constructed such that it contains every vertex just once. Thus, **Semi-Hamiltonian** Graphs  allows vertices to be used more than once.

Common problems solved through the concept of Eulerian and Hamiltonian graphs such as **The shortest path problem, The chinese postman problem** and 	**The travelling salesman problem.**

**Trees** and **Forests** types of graphs and the proof of the total number of labelled trees of n vertices being n<sup>n-2</sup>. Furthermore the application of these tree graphs to enumerate the number of alkanes that can be formed from the formula of **C**<sub>n</sub>**H**<sub>2n+2</sub> shows the application of these types of graphs.

Problems using the theory of tree graphs such as The minimum connector problem, solved using a type of algorithm called the greedy algorithm, Electrical circuits and Searching Trees, using breadth- first search and depth-first search methods.

### Text 2 :- _The Design and Analysis of Computer Algorithms by Alfred V. Aho, John E. Hopcraft and Jeffrey D. Ullman_

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

## CHECKPOINT 2 (11th April - 6th June)

### Topic 1 :- _Image Processing_

Image processing using basic Python libraries such as NumPy and matplotlib. In this I learned to import and store images as arrays of numbers and display them accordingly. 
All the different types of transformations I learned through this are-

1. Image Filpping (both vertically and horizontally)
2. Colour Inversion
3. Comverting colour images to grayscale 
4. Image Cropping 
5. Image Scaling (both up and down)
6. Blurring 
7. Creating Borders using NumPy 
8. Thresholding

These are some of the basic image processing techniques used. All of these examples can be found in the Jupyter Notebook- Image Processing in Python without OpenCV.

### Topic 2 :- _Image Processing Using OpenCV_

OpenCV is a Python library widely used for image processing. It has built in functions which tackle most of the image processing issues. 
Topic 2 was mainly focused on learning openCV and using it in Image Processing for all the dfferent above mentioned techniques. 
All of the applications of this OpenCV library can be found in the Jupyter Notebook- Image Processing Using OpenCV. 

### Topic 3 :- _Continung in OpenCV_

In this topic we take upon some of the harder concepts of Image Processing such as scaling and Thresholding.
We use different types of Thresholding types such as Otsu Thresholding and Simple Thresholding.
Further in scaling =, we also loop upon rataing and translating images using OpenCV.
Another concept we learnt in this was of the Histogram Equalisation, in this we somewhat equalize the contrast of the image across all the pixels.

### Websites used for some concepts

1. OpenCV - https://docs.opencv.org/4.5.2/d9/df8/tutorial_root.html
2. Thresholding - https://www.geeksforgeeks.org/python-thresholding-techniques-using-opencv-set-1-simple-thresholding/
3. Otsu Thresholding - https://learnopencv.com/otsu-thresholding-with-opencv/

# CHECKPOINT 3 (30th June - 15th July)

### Topic 1 - _Edge Detection_

In this topic I learned about the different edge detection methods used in Image Processing using OpenCV. 
Two main different types of edge detection techniques widely used are -

1. Canny Edge Detection
2. Sobel Edge Detection 

### Websites used for some concepts 

1. OpenCV - https://docs.opencv.org/4.5.2/d9/df8/tutorial_root.html
2. Canny - https://www.geeksforgeeks.org/implement-canny-edge-detector-in-python-using-opencv/
3. Sobel - https://www.geeksforgeeks.org/python-program-to-detect-the-edges-of-an-image-using-opencv-sobel-edge-detection/

### Topic 2 - _Point Clouds_

A point cloud is a set of data points in space. The points may represent a 3D shape or object. Each point position has its set of Cartesian coordinates (X, Y, Z). Point clouds are generally produced by 3D scanners or by photogrammetry software, which measure many points on the external surfaces of objects around them. As the output of 3D scanning processes, point clouds are used for many purposes, including to create 3D CAD models for manufactured parts, for metrology and quality inspection, and for a multitude of visualization, animation, rendering and mass customization applications. Point clouds can be acquired from hardware sensors such as stereo cameras, 3D scanners, or time-of-flight cameras, or generated from a computer program synthetically. 

To use point clouds we used the software CloudCompare. 

![CloudCompare](Images/2021-07-18.png?raw=true "Title")

I used the pre-constructed point cloud resource provided by https://help.sketchup.com/en/scan-essentials-sketchup/sample-point-cloud-data. The parking lot point cloud has been taken from here. Point clouds can be used to nevigate around the image as in a real 3D world. 

### Websites Used are

1. Point Clouds - https://help.sketchup.com/en/scan-essentials-sketchup/sample-point-cloud-data
2. Cloud Compare - https://www.danielgm.net/cc/
3. Visual SFM - https://d32ogoqmya1dw8.cloudfront.net/files/getsi/teaching_materials/high-rez-topo/visual_sfm_tutorial.pdf
4. Point Clouds - https://pointclouds.org/about/
