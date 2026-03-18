# Introduction
This project aim was to create an algorithm for implementing the neighbor joining method to build a phylogenetic tree. FASTA files are read in, Smith-Waterman scores are calculated and converted to distance scores, and a Newick string is produced to represent relatedness. The program then produces a graphical representation of the unrooted tree.

# Pseudocode
Put pseudocode in this box:

```
Some pseudocode here
```

# Successes
We met several times for brainstorming and group programming, and ingestigated both iterative and recursive methods which lent us a greater understanding of the algorithm.

# Struggles
Our first stumbling block was that we noticed that the lecture didn't mention Q-matrices which were mentioned in the notebook as well as external resources about neighbor joining, so we spent a lot of time trying to understand how Q-matrices interacted with the methods described in the lecture. 
We also spent a good amount of time trying to decide on Node object structure and how best to point between child and parent nodes, and how that would affect our ability to build the Newick string.

# Personal Reflections
## Nicholas Bottomley 
Group leader's reflection on the project

## Hongyuan Deng 
Reflecting on this module, our team spent a significant amount of time wrestling with the algorithmic design of the Neighbor-Joining (NJ) function, specifically deciding between a recursive and an iterative approach.However, through deep diving into the implementation,we utilized an iterative "string-building" technique. By dynamically updating the numpy distance matrix and formatting the merged nodes directly into Newick substrings on the fly, we bypassed the deep recursion limits in Python.

## Victoria Van Berlo
This project seemed simple, but proved rather confounding the deeper we went. Recursion is a weakness of mine, but my group members helped me to understand and having both methods solidified things for me.

# Generative AI Appendix
As per the syllabus
