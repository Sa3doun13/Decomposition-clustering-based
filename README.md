# Decomposition-clustering-based

This work applies a decomposition approach for solving the Job-shop Scheduling Problem (JSP).
It defines the similarities/dissimilarities between the operations and assign the most similar operations into the same cluster. This has been accomplished by extracting a set of features from the problem itself or from solutions obtained by other heuristics such as (FIFO, MTWR or EST). After the assignment process, the problem is solved using a scheduler developed in Answer Set Programming (ASP).

The project contains the following folders:

<table>
<tr><th>File/Folder name</th><th>File description</th></tr>
<tr><td>README.md</td><td>text version of this file</td></tr>
<tr><td>assign_to_clus</td><td>contains the "lp" files which represent the assignment of the operations into clusters</td></tr>
<tr><td>dispatching_rules</td><td>a folder has the implementation of the FIFO and MTWR heuristics</td></tr>
<tr><td>dispatching_rule/FIFO.py</td><td>a python file contains the implementation of the kMeans algorithm developed by Mohammed</td></tr>
<tr><td>est_solution</td><td>a folder contains the solution of the instances obtained by EST heuristic</td></tr>
<tr><td>instances</td><td>a folder has the instances files</td></tr>

<tr><td>splncs04.bst</td><td>current LNCS BibTeX style with alphabetic sorting</td></tr>
</table>

