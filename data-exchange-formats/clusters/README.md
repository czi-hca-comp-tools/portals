# Cluster file format specification

A file format to define cluster membership of cells in single-cell expression experiments. 

In the first instance to be a simple cell ID to cluster ID in .tsv format, with additional optional fields for e.g. probability of assignment. However the format should be standard and formalised as per similar efforts: https://github.com/samtools/hts-specs.  

Ideally to also form a modular component of [a trajectories format](../trajectories/README.md), or utility scripts associated with the trajectories format should be able to read this format and incorporate it.
