Matrix Multiplication Kernel
======================

**Texas Tech University, CS5375 Computer Systems Organization and Architecture, Project**

* JAGADEESH MADDINENI 
* R11788222
* jmaddine@ttu.edu

## CPU Code Execution
1. Initial step is to conenct HPCC using e-raider credentials
2. clone the project **git clone https://github.com/jagadeesh0128/CS5375_GPU_Lecture.git**
3. once clone the project then will have enter to the file **CS5375_GPU_Lecture**.
4. ls
5. g++ martix_Mul_cpu.cpp -o matrixMul_cpu.exe
6. ./matrixMul_cpu.exe
7. time ./matrixMul_cpu.exe
8. All the results are saved in .txt format for your reference.

## PART1

the below are the commands to exectute the requirements of Part1.
g++ matrixMul_cpp.cpp -o matrixMul_cpu.exe // run the command to execute the given CPP file and store the output in .exe format
./matrixMul_cpu.exe // To display the run time
interactive -p gpu-build // To execute the cuda file
nvcc matrixMul_gpu.cu -o matrixMul_gpu.exe // To execute the cuda file and output stored in the .exe format
./matrixMul_gpu.exe //To compute and display the execution time
nprof ./matrixMul.gpu.exe // To profiling

## PART2

nvcc matrixMul_gpu_part2.cu -o matrixMul_gpu_part2.exe //To compile the code
./matrixMul_gpu_part2.exe // To compile and display the average time
nvprof ./matrix_gpu_part2.exe // For Profiling the requirements


## PART3

nvcc matrixMul.gpu_part3.cu -o matrixMul_gpu_part3.exe // To execute the code
./matrixMul_gpu_part3.exe // To compile and display the average time
nvprof ./matrix_gpu_part3.exe // For Profiling the requirements

## PART4

nvcc matrixMul.gpu_part4.cu -o matrixMul_gpu_part4.exe // To execute the code
./matrixMul_gpu_part4.exe // To compile and display the average time
nvprof ./matrix_gpu_part4.exe // For Profiling the requirements


