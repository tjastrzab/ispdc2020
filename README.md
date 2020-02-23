# ispdc2020

This repository contains the hexapeptide test sets used for the experiments described in the paper submitted to ISPDC 2020.

The files are named according to the following convention:
- sample-[size]-plus.txt - a set of examples S_+, where [size] takes on the value 10, 20, ..., 100
- sample-[size]-minus.txt - a set of examples S_-, where [size] takes on the value 10, 20, ..., 100

Each line in the file represents a different word belonging to the set S_+ or S_-. The end of word is marked by -1.
The line containing only the -1 value denotes the end of the input set.
