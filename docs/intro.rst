Introduction
============

The ddot (Data-Driven Ontology Toolkit) package makes the construction, analysis, and manipulation of ontologies simple.

The ddot package is both a Python library and a set of REST web-services that wrap around the Python library.

Dependencies
============
1. cxmate (optional for web-services)
2. 

Features
========

1. Reading, writing, and conversion of data-driven ontologies
   a. Parse OBO files
   b. Conversion to and from flat table files, NetworkX, igraph
   c. Interface with the NDEx_ (Network Database Exchange). 

.. _NDEx: http://public.ndexbio.org

2. Construction of data-driven ontologies using the CLIXO algorithm

3. Alignment of two ontologies

4. Basic manipulations
   a. Propagate gene annotations
   b. Calculate statistics like term sizes and balance
   c. Identify a spanning tree for visualization
   d. Collapsing ontology to non-redundant terms

5. Expand set of seed genes

6. Convert genotypes to ontotypes.

7. Set of REST web-services that interface with networks in NDEx_ 

Examples
========

Jupyter notebooks

1. Parse Gene Ontology and upload to NDEx
2. Characterize Fanconi Anemia
3. Autophagy
4. Construct ontotypes from Yu et al.

References
==========

1. Kramer et al.
2. Yu et al.