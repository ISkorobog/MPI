mpicc main.c -o mpi.exe
mpiexec -np (n) ./mpi.exe example.txt > out(n).txt
