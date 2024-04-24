To run OPEMP code :
g++ -fopenmp filename.cpp -o filename
./filename 

To run CUDA :
nvcc filename.cu -o filename
./filename


Header Files for CUDA: 
#include <iostream>
#include <vector>
#include <cuda_runtime.h>
