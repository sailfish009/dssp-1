DSSP version 4
==============

This is a rewrite of DSSP, now offering full mmCIF support. The difference
with previous releases of DSSP is that it now writes out an annotated mmCIF
file by default, storing the secondary structure information in the 
_struct_conf category.

Building
--------
To build this, first install [@https://github.com/PDB-REDO/libcifpp.git libcif++]
and then run `configure`, `make` and `make install`.
