# EXCITING-Plus :: branch - serial

This branch is created for compiling and running the code on a personal laptop or desktop computer. 

You need a Fortran compiler gfortran/ifort, or MPI compiler like mpif90. If it's compiled with mpif90 then you have MPI support. If it's compiled with gfortran/ifort then the it only runs in serial mode. Check make.inc.serial. 

It has been tested with gfortran and mpif90 (mpif90 from OpenMPI installed using gcc/g++/gfortran).  
