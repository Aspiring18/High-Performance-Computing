To run OPEMP code :
1) g++ -fopenmp filename.cpp -o filename
2) ./filename 

To run CUDA :
1) nvcc filename.cu -o filename
2) ./filename

To run on Terminal For CUDA:
//Terminal: nvcc -o file file.cu
//./file

Header Files for CUDA: 
#include <iostream>
#include <vector>
#include <cuda_runtime.h>
