#include <stdlib.h>
#include <stdio.h>

int main() {
	// variaveis declaradas;
	int X , valor;
	//função para receber o valor do usuario.
	scanf("%d", &valor);
	//condição do loop que será dado para efetuar a fatoração.
	for (X=1; valor>1; valor--){
		X = X * valor;
	}
	 printf("%d\n",X);
	 system("pause");
}
