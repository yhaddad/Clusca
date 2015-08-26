
1. Prerequisites
2. Building
3. Installing
4. Contributing
 
## PREREQUISITES

 This project requires:
  * Cross-platform Make (CMake) v2.6.2+
  * GNU Make or equivalent.
  * GCC or an alternative, reasonably conformant C++ compiler.
  * Boost C++ Libraries v1.37+ [HEADERS and LIBRARIES]
  
## BUILDING 
 This project uses the Cross-platform Make (CMake) build system. However, we
 have conveniently provided a wrapper configure script and Makefile so that
 the typical build invocation of "./configure" followed by "make" will work.
 For a list of all possible build targets, use the command "make help".

 NOTE: Users of CMake may believe that the top-level Makefile has been
 generated by CMake; it hasn't, so please do not delete that file.

## INSTALLING

 Once the project has been built (see "BUILDING"), execute "sudo make install".

## CONTRIBUTING
 TODO:
	* implement graph data format
	* kd-tree neighbour searching
	* Include dependence on root
	