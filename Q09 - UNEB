/* Faça um algoritmo que leia 3 valores a, b e c, lados de um triangulo, e
verifique o tipo de triângulo formado escrevendo: 0 - se o triângulo é equilátero
(os três lados são iguais); 1 - se o triângulo é isóscele (dois lados iguais e um
diferente);2 - escaleno (3 lados diferentes).*/

#include <stdio.h>
#include <locale.h>
#include <math.h>

float l1, l2, l3;

int main(){
	setlocale(LC_ALL,"");
	printf("Digite o valor do lado 1: ");
	scanf("%f", &l1);
	printf("Digite o valor do lado 2: ");
	scanf("%f", &l2);
	printf("Digite o valor do lado 3: ");
	scanf("%f", &l3);
	if(l1 != l2 && l1 != l3 && l2 != l3){
		printf("2");
	} else if(l1 == l2 && l1 == l3 && l2 == l3){
		printf("0");
	} else if(l1 == l2 && l1 != l3){
		printf("1");
	} else if(l1 == l3 && l1 != l2){
		printf("1");
	} else if(l2 == l3 && l2 != l1){
		printf("1");
	}
}
