/*Faça um algoritmo que leia 3 valores a, b e c, lados de um triangulo, e
verifique o tipo de triângulo formado escrevendo: 0 - se o triângulo é retângulo
2 (A^2=B^2+C^2); 1 - se o triângulo é acutângulo (A^2 > B^2 + C^2) ;2 -
obtusângulo (A^2 < B^2 + C^2). Considere que, para aplicar as relações
mostradas, algoritmo deve garantir que o maior dos 3 lados estará em A.*/

#include <stdio.h>
#include <locale.h>

float a, b, c, aa, bb, cc;

int main(){
	setlocale(LC_ALL, "");
	printf("Digite o valor de lado A: ");
	scanf("%f", &aa);
	printf("Digite o valor de lado b: ");
	scanf("%f", &bb);
	printf("Digite o valor de lado c: ");
	scanf("%f", &cc);
	if(aa > bb && aa > cc){
		a = aa;
		b = bb;
		c = cc;
		if((a*a) == (b*b) + (c*c)){
		printf("0\n");
	} else if((a*a) > (b*b) + (c*c)){
		printf("1\n");
	} else if ((a*a) < (b*b) + (c*c)){
		printf("2\n");
	}	
	} else if(bb > aa && bb > cc){
		a = bb;
		b = aa;
		c = cc;
		if((a*a) == (b*b) + (c*c)){
		printf("0\n");
	} else if((a*a) > (b*b) + (c*c)){
		printf("1\n");
	} else if ((a*a) < (b*b) + (c*c)){
		printf("2\n");
	}
	} else if(cc > aa && cc > bb){
		a = cc;
		b = aa;
		c = bb;
		if((a*a) == (b*b) + (c*c)){
		printf("0\n");
	} else if((a*a) > (b*b) + (c*c)){
		printf("1\n");
	} else if ((a*a) < (b*b) + (c*c)){
		printf("2\n");
		
	};
	};
	printf("%.1f", a);
}
