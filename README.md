#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main() {
	int nota1, nota2, total;
	
	printf("Digite o primeiro valor: ");
	scanf("%d", &nota1);
	
    printf("Digite o segundo valor: ");
	scanf("%d", &nota2);

	total = nota1 + nota2;
	
  /* %d puxar o numero inteiro */
  /* %f puxar numero decimal */
  /* scanf pegar numero digitado */
   	
	printf("O Valor Total E: %d ", total);
	
return 0;
}
