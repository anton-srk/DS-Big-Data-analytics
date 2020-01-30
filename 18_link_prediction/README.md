# HW 18: Link Prediction

* Solve a link prediction problem using the data from the _social_network_11.csv_ file.

The code is organized is follows:

_hw18_edge_removal_ contains the solution based on the removal of the existing edges in the graph and a consequent attempt of their prediction;

_hw18_train_test_ contains the solution based on listing all the possible pairs of the nodes, denoting an edge as _1_ and its absence as _0_, splitting the resulting dataset in train/test, and solving a classification problem as usual.
