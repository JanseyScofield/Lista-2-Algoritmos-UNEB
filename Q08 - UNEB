/*Faça um algoritmo que leia 3 valores a, b e c, coeficientes de uma equação
de segundo grau, e verifique se a equação tem raízes reais. Se a equação
tiver raízes reais, calcule e escreva as raízes da equação. Se não tiver, escreva
"A equação não possui raízes reais". Dica: As raízes de uma equação podem
ser calculadas pela fórmula de Baskhara. Uma equação não possui raízes se
reais se B*B-4*a*c < 0*/


#include <stdio.h>
#include <locale.h>
#include <math.h>
float a, b, c;
float r1, r2;
float x;
int main(){
	setlocale(LC_ALL,"");
	printf("Digite o valor de a: \n");
	scanf("%f", &a);
	printf("Digite o valor de b: \n");
	scanf("%f", &b);
	printf("Digite o valor de c: \n");
	scanf("%f", &c);
	if (((b*b) - 4*a*c) < 0){
		printf("A equação não possui raízes reais");
	} else if (((b*b) - 4*a*c) >= 0){
		x = ((b*b) - 4*a*c);
		r1 = ((-b) + (sqrt(x)))/ (2 * a);
		r2 = ((-b) - (sqrt(x)))/ (2 * a);
		printf("A equação tem raízes: \n Raiz 1: %0.1f.\n Raiz 2: %0.1f", r1, r2);
	}
}
