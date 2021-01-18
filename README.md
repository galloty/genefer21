# genefer21
Generalized Fermat Prime search program

## About

**genefer21** is an [OpenMP®] (https://www.openmp.org/) and [OpenCL™](https://www.khronos.org/opencl/) application.  
It performs a fast probable primality test for numbers of the form *b*<sup>2<sup>*n*</sup></sup> + 1 with [Fermat test](https://en.wikipedia.org/wiki/Fermat_primality_test).  
[genefer](https://primes.utm.edu/bios/page.php?id=2740) was created by Yves Gallot in 2001. It has been extensively used by [PrimeGrid](https://www.primegrid.com/forum_forum.php?id=75) computing project.  
genefer21 is a new highly optimised CPU and GPU application, created in 2021. Robert Gerbicz error checking is implemented in base-*b* and an Anti-Cheat validation (Pavel Atnashev) with verifiable delay function (Krzysztof Pietrzak) is included for distributed projects.  

## Build

genefer21 is under development...  
Any number of the form *b*<sup>2<sup>*n*</sup></sup> + 1 such that 2 &le; *b* < 2,000,000,000 and 15 &le; *n* &le; 23 can be tested.  
*This version was compiled with gcc and tested on Windows and Linux (Ubuntu).*  
An OpenCL SDK is not required. OpenCL header files are included in the project and the application can be linked with the dynamic OpenCL library of the OS.

## TODO

- ...