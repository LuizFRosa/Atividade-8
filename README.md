# Atividade-8

#include <stdio.h>
#include <stdlib.h>

int main() {
	
    float numero;

	printf("escolha um numero para ver a tabuada dele \n");
	scanf("%f",& numero);

    int tabuada [] = {1,2,3,4,5,6,7,8,9,10};

    int i=1;

	while( i < 10){
			
	printf("%.2f x %d = %.2f\n", numero, tabuada[i], numero * tabuada[i]);
			
	i++;		
	
}
    
    return 0;
}
