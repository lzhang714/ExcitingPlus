# EXCITING-Plus :: branch - serial

This branch is created for compiling and running the code IN SERIAL on a personal laptop or desktop computer. 

You STILL NEED a MPI compiler like mpif90. 

It has been tested with OpenMPI installed using GNU compilers gcc/g++/gfortran.  

Note the code does not have distribution of any job. For example, if you run it using 4 ranks like "mpirun -np 4", it will simply run 4 copies of the whole calculation on 4 cores. So, using one rank is enough, i.e. "mpirun -np 1".
