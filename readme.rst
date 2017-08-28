PyNE: The Nuclear Engineering Toolkit
=====================================
The PyNE project aims to provide a common set of tools for nuclear 
science and engineering needs.

If you are interested in the package itself, or would like to help
and contribute, please let us know either on the mailing list 
(https://groups.google.com/forum/#!forum/pyne-dev, 
pyne-dev@googlegroups.com) or `github`_.

PyNE:data
=========
This repository aims to store all data pertinent during an
installation of PyNE. If features are added to PyNE that
rely upon static data items, such as decay.tar.gz, they
should be added to this repository

decay.tar.gz
============
To produce the decay.tar.gz run the following command from the
PyNE /src directory
::
   python decaygen.py
   
Then tar up the decay.cpp and decay.h files
::
   tar -pczf decay.tar.gz decay.cpp decay.h
  
Then add and commit them to this repository
