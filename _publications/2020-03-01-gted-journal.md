---
title: "Graph traversal edit distance and extensions"
collection: publications
category: manuscripts
permalink: /publication/2020-03-11-gted-journal
excerpt: ''
date: 2020-03-11
venue: Journal of Computational Biology 
paperurl: 'https://www.liebertpub.com/doi/full/10.1089/cmb.2019.0511'
citation: 'Ebrahimpour Boroojeny, A., Shrestha, A., Sharifi-Zarchi, A., Gallagher, S. R., Sahinalp, S. C., &amp; Chitsaz, H. (2020). Graph traversal edit distance and extensions. Journal of Computational Biology, 27(3), 317-329.'
---

Many problems in applied machine learning deal with graphs (also called networks), including social networks, security, web data mining, protein function prediction, and genome informatics. The kernel paradigm beautifully decouples the learning algorithm from the underlying geometric space, which renders graph kernels important for the aforementioned applications. In this article, we give a new graph kernel, which we call graph traversal edit distance (GTED). We introduce the GTED problem and give the first polynomial time algorithm for it. Informally, the GTED is the minimum edit distance between two strings formed by the edge labels of respective Eulerian traversals of the two graphs. Also, GTED is motivated by and provides the first mathematical formalism for sequence co-assembly and de novo variation detection in bioinformatics. We demonstrate that GTED admits a polynomial time algorithm using a linear program in the graph product space that is guaranteed to yield an integer solution. To the best of our knowledge, this is the first approach to this problem. We also give a linear programming relaxation algorithm for a lower bound on GTED. We use GTED as a graph kernel and evaluate it by computing the accuracy of a support vector machine (SVM) classifier on a few data sets in the literature. Our results suggest that our kernel outperforms many of the common graph kernels in the tested data sets. As a second set of experiments, we successfully cluster viral genomes using GTED on their assembly graphs obtained from de novo assembly of next-generation sequencing reads.
