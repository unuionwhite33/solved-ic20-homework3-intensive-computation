Download Link: https://assignmentchef.com/product/solved-ic20-homework3-intensive-computation
<br>
<strong>Exercise 1 </strong>

Write the <strong>function</strong> <strong>epair</strong> that:

<ul>

 <li>takes a matrix as <strong>input</strong></li>

 <li>computes the largest absolute eigenvalue and the corresponding eigenvector implementing the <strong>Power method</strong></li>

 <li>gives as <strong>output</strong> the maximum absolute eigenvalue and the corresponding eigenvector</li>

</ul>

Write the <strong>function</strong> <strong>deflation</strong> that:

<ul>

 <li>takes as <strong>input:</strong> a matrix, the largest eigenvalue and the corresponding eigenvector</li>

 <li>computes the second largest eigenvalue and the corresponding eigenvector implementing one <strong>Deflation method</strong></li>

 <li>gives as <strong>output</strong> the second eigenvalue and the corresponding eigenvector</li>

</ul>

Write a script calling the two functions <strong>epair</strong> and <strong>deflation</strong> on sets of random matrices of different size (for example 25, 50, 75, 100).

To compare the obtained values with those produced by the function <strong>eig</strong> of Matlab, compute the difference between the largest eigenvalue obtained with your method and with matlab (error) and average on the sets of matrices of the same size.

Plot the values of errors on a graph, showing also the <em>error bar</em> (to show the minimum and maximum values).




<strong>Exercise 2 – Gould index for eigenvector centrality and Fiedler eigenvector for Graph Partitioning </strong>

Write a script that:

<ul>

 <li>defines a <strong>random adjacency matrix M</strong> corresponding to a graph, representing a set of towns and the travel routes among these towns</li>

 <li>determines the most accessible town using the Gould index, calling the <strong>function</strong> <strong>epair</strong> to obtain the principal eigenvector x1 on the appropriately modified adjacency matrix</li>

</ul>

<strong>Reference: </strong><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">http://matrixapps.blogspot.it/2010/07/gould</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">–</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">index</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">–</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">matrix</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">–</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">application</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">–</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">to.html</a><a href="https://matrixapps.blogspot.it/2010/07/gould-index-matrix-application-to.html">)</a>

<ul>

 <li>partitions the graph into two parts according to <strong>the Fiedler eigenvector</strong> (eigenvector corresponding to the second smallest eigenvector) obtained by considering the Laplacian matrix and using the <strong>function</strong> <strong>epair </strong>and the<strong> function</strong> <strong>deflation</strong></li>

 <li>gives as <strong>output</strong> four subplots in a graphical window, one with the representation of the considered graph where the most accessible town is highlighted, the other three with the two parts of the bi-partitioned graph are represented using different colors using the three method to divide the Fiedler eigenvector (positive-negative, mean, median).</li>

</ul>

<h1>Observations</h1>

 Use <strong>graph </strong>to define graphs and <strong>gplot</strong> to draw graphs.