# sort_mpi
Trabalho 2 da disciplina de Programação Paralela - PUCRS - 2019-2

O objetivo do trabalho é implementar um programa paralelo utilizando MPI para ordenar um vetor e avaliar o ganho de desempenho em nodos multiprocessados do cluster Grad.

Execute o programa conforme exemplo abaixo:

**mpirun -np 4 run 10 1**

onde:
    
    np é o numero de processos (neste caso, 4 está considerando o nó mestre. Para paralelizar com 4 processos, informe np 5).

    run é o nome do programa

    10 eh o tamanho do vetor

    1 informa se quer imprimir no arquivo de saida, 0 para não imprimir nada