# AmoCoalaPy
An algorithm that calculates the probability of cophylogeny reconstruction events based on ABC approach for host-parasyte associations.
This is a python version (3.6.13) of an already existing algorithm written in java. It makes use of ETE-3 Toolkit for phylogenetic trees.

In the current version, the algorithm reads a nexus file of "Jane / TreeMap Nexus" format 
(more info about the format in the first section of this document: https://team.inria.fr/erable/files/2020/11/Input-File.pdf)
and after starting from the root of the host tree it generates a parasyte tree based on the probabilities of Cospeciation, Duplication and Loss event.

The Host-Switch event as it is right now has not been implemented yet.

This is still a work in progress.

More details about the algorithm functionality are showed in the following links below:

Cophylogeny Reconstruction via an Approximate Bayesian Computation: https://academic.oup.com/sysbio/article/64/3/416/1631550?login=true

Cophylogeny Reconstruction Allowing for Multiple Associations Through Approximate Bayesian Computation: https://arxiv.org/abs/2205.11084


AmoCoala.java: https://team.inria.fr/erable/en/software/amocoala/
ETE-3 Toolkit: https://github.com/etetoolkit/ete
