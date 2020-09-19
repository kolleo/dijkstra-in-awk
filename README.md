# An awk script for Dijkstra's algorithm
## Introduction
This is a tiny 'playground project' to teach myself some basics of ***awk***.
I have taken ***Dijkstra's algorithm*** as the field of application.
My script generates all ***shortest path lengths*** in a ***graph***.

## awk
Awk is a well-known Unix/Linux command line utility, and a real programming language too. 
It was actually invented for processing/filtering line oriented text files.
See [AWK](https://en.wikipedia.org/wiki/AWK) for more information.

## Dijkstra's algorithm
This is a famous algorithm in ***algorithmic graph theory***, invented by ***E. W. Dijkstra***.
When a ***directed or undirected graph with weighted edges*** is given, the algorithm determines, 
starting with vertex *u*, all shortest path lengths to all vertices of the graph.
See [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm) for more information.

## How to run the awk script
> I assume you have the gawk implementation of awk!

In a **bash shell** enter

    awk -f dijkstra.awk  

to get some help.

Have fun!  
*-- Oliver Kolle*
