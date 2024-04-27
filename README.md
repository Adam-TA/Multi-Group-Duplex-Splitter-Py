# Multi-Group-Duplex-Splitter-Py
Python implementation of a generalized Duplex algorithm, inspired by Snee's work (1977). It enables deterministic splitting of data into any number of groups of arbitrary sizes while preserving the original dataset's characteristics.

The algorithm partitions a dataset into mutually exclusive subsets through a stepwise process of distributing data points from the original dataset. At each iteration, the subset with the least filledness relative to its capacity selects a data point from the remaining pool, opting for the one farthest from the current data points within the subset.
