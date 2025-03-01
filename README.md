# HEDSATS
High Energy Density Semi-Analytical Thermal Solution library

Contained within this repository are a series of semi-analytical thermal solutions to heat conduction problems representative of high energy density advanced manufacturing processes.

The solutions utilise various combinations of Laplace transform, Eigen value problem and method of images based solutions to compute the transient thermal response to volumetric heat sources in orthogonal three dimensional domains.

The relevant works pertaining to this software are:

https://doi.org/10.1016/j.jmatprotec.2017.02.002

https://doi.org/10.1016/j.ijthermalsci.2017.09.012

https://doi.org/10.1016/j.ijthermalsci.2018.12.049


The software is intended to increase the use of Green's function based thermal analysis techniques in scenarios where their application is appropriate.

Various example applications are included in the release which demonstrate how a user may call the functions in HEDSATS which return the solutions to the 3D transient heat equation with the application of various distributed heat sources. The only requirement for compilation of the code, including the example applications is a c++ compiler such as GCC or intel etc. A GNU makefile is included with each example for use with the make utility. typing 'make' in the example folder from a unix OS should build the application. 

Development of the library of solutions is ongoing, including the addition of further boundary condition combinations, heat source models etc.

Please direct any questions or comments to Dr Tom Flint at the Universiy of Manchester (thomas.flint@manchester.ac.uk)
