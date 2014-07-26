Traversing Mazes the Pythonic Way and other algorithmic adventures
=============================

## EuroPython 2014 talk

All the slides are collected in the `TraversingMazesThePythonWay.ipynb`
iPython notebook.

To generate the HTML version of the slides you need to apply the following
command:

    ipython nbconvert ./TraversingMazesThePythonWay.ipynb --to slides --post serve --config slides_config.py
    
    
Please note that this command is also embedded in the **first** cell of the notebook to allow
for an *inline* HTML slides generation.

Finally, click [here](http://nbviewer.ipython.org/github/valeriomaggio/traversing-mazes-pythonic-way/blob/master/TraversingMazesThePythonWay.ipynb)
to see the slides on **nbviewer**.

## Abstract

**Graphs** define a powerful mental (and mathematical) model of structure, 
representing the building blocks of formulations and/or solutions 
for many *hard problems*. In this talk, graphs and (*some of the*) main 
graph-related algorithms will be analyzed from a **very pythonic** angle:
the [Zen of Python][1] (e.g., *beautiful is better than ugly*, 
*simple is better than complex*, *readability counts*).

[1]: http://www.python.org/dev/peps/pep-0020/ "PEP20: The Zen of Python"

## Description ##

Programming isn't just about software architectures and object-oriented design;
it is also about solving algorithmic problems *efficiently*, some of which 
are really *hard* [[Hetland, 2010]][0].

The way we decide to *represent* and to *solve* our problems 
(i.e., the *data structure* and the *algorithm* we use, respectively)
has a great impact on the overall *complexity* of our solution.

In this scenario, **graphs** define a powerful mental (and mathematical)
model to deal with many algorithmic problems: "if we can formulate a problem as 
one dealing with graphs, even if it doesn't *look* like a graph problem, we 
are probably one step closer to solving it." [[Hetland, 2010]][0].

Indeed, graphs constitute the building blocks for many (*hard*) problems. 
Thus, mastering graphs and graph algorithms (e.g., graph traversals) provides a 
jump start to deal with many other problems, such as 
*finding the shortest path to get out from a dungeon in a `D&D` story* [^1].	

With particular considerations to the authoritative books on this subject (such 
as the classics by *T. Cormen* and *S.S. Skiena*) for the theoretical 
part (actually intended to be very limited and mostly referenced), this talk 
aims at providing an overview of graphs and main graph-based algorithms for 
Python programmers.

The general outline of the talk will cover the following topics:

*    Implementing Graphs and Trees;
*    "DRY" Algorithms
    *    "Memoization" and "Dynamic Programming"
*    "Mazes" Traversals and Search
    *    Graph Traversals
    *    Shortest Path Algorithms

The main goal of the talk is to analyse how one of the most fundamental (data)
structure of "ADS" university classes, may be handled (and implemented) in a 
**very pythonic way**, in accordance with the [Zen of Python][1] (e.g., 
*beautiful is better than ugly*, *simple is better than complex*, *readability counts*).

To this end, code examples and case studies will be presented during the talk
to encourage the discussion and to stimulate the attendees to come up with 
different solutions.

Very basic math skills are required, together with familiarity with programming
in general and with Python in particular.

[0]: http://goo.gl/ZeuDNc "Hetland, M. L., Python Algorithms, Mastering the Basic Algorithms in the Python Language, Apress 2010"
[1]: http://www.python.org/dev/peps/pep-0020/ "PEP20: The Zen of Python"

[^1]: "Please replace D&D with your favorite RPG. D&D may sound old fashioned :)"

#### Author: Valerio Maggio (@leriomaggio)
