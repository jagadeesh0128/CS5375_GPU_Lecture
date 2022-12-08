all: part1_cpu part1_gpu part2_gpu part3_gpu part4_gpu

part1_cpu:
	g++ matrixMul_cpu.cpp -o matrixMul_cpu.exe
part1_gpu:
	nvcc matrixMul_gpu.cu -o matrixMul_gpu.exe
part2_gpu:
	nvcc matrixMul_gpu_part2.cu -o matrixMul_gpu_part2.exe
part3_gpu:
	nvcc matrixMul_gpu_part3.cu -o matrixMul_gpu_part3.exe
part4_gpu:
	nvcc matrixMul_gpu_part4.cu -o matrixMul_gpu_part4.exe



