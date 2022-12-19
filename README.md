## Introduction
Sequence alignment is a technique used in bioinformatics to compare and analyze DNA, RNA,
or protein sequences. The goal is to identify similarities between the sequences that may be a
consequence of functional, structural, or evolutionary relationships. In this process, the sequences
are arranged in a matrix, with gaps inserted between the residues to align similar characters in
successive columns. Sequence alignment can also be used to compare and analyze non-biological
sequences, such as the distance between strings in natural language or financial data. If two
sequences in an alignment have a shared ancestry, the similarities in characters are matches. The
differences between them can be analyzed as point mutations or indels (insertions or deletions) that
have occurred in one or both lineages since they diverged from a common ancestor. Mismatches
between the sequences can be interpreted as point mutations, while gaps in the alignment can be
understood as indels introduced over time. Proteins consist of amino acid chains, and aligning the
amino acid sequences of related proteins may show which regions have functional or structural
importance. Gene sequences are aligned to find regions of similarity, which may help to indicate if
the genes are related. Sequence alignments are also used in the field of phylogenetics to construct
and interpret phylogenetic trees.

### Limitations and Inspirations from existing webtools:
(1) The [web tool](https://github.com/drdrsh/Needleman-Wunsch) is a very detailed and enhanced visualization with highly interactive Dynamic Programming table that not only displays the values but also gives the possible traceback direction from each cell. However, this tool is implementation of a single algorithm, Global alignment, which ideally produces a unique solution with a unique path and alignment.
(2) [Another tool](https://github.com/Valiec/AlignmentVisualizer) that effectively implements multiple alignment algorithms is available for Global, Local and Fitting alignments. This also provides the feasibility of defining the custom scoring matrix, i.e. to define the match score and mismatch/gap penalties. On the downside, this implementation facilitates an alignment only with A,C,T,G characters, which might not be helpful for research and academic purposes. Another significant limitation and also a motivation in this project is that, for fitting and local alignments, it is possible that there can be multiple optimal paths based on the choice of start and end points in the traceback solution, which is not currently implemented in the tool.

An interactive demo of the application can be viewed [here](https://639f95e5580637635f234415--stupendous-faloodeh-256a5a.netlify.app/).
It is hosted using Netlify.

## Screenshots from the tool:
### Global Alignment
![Global](https://github.com/SINDHUSITA/Sequence-Alignment-Algorithms/blob/master/demoImages/FirstPage.png)
### Fitting Alignment with Multiple Paths
![Fitting](https://github.com/SINDHUSITA/Sequence-Alignment-Algorithms/blob/master/demoImages/fittingCollage.jpg)
### Local Alignment with Multiple Paths
![Local](https://github.com/SINDHUSITA/Sequence-Alignment-Algorithms/blob/master/demoImages/localCollage.jpg)
