TRABALHANDO COM VET E SRAND, NUMEROS ALEATORIOS DA POSIÇÃO 5
ads-3s

#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#define N 5

int main()
{
	


int vet[N];

srand(time(NULL));
for (int i = 0; i < N; i++){
	vet[i]= rand() %6;
	printf("%d\n", vet[i]);

}
}
