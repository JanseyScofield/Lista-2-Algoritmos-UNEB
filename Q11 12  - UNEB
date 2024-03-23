/*Faça um algoritmo que leia 3 valores l1, l2 e l3 e verifique se formam um
triângulo e, se formarem, o tipo de triângulo formado, escreva: 0 - se não
formarem triângulo; 1 - se formarem um triângulo equilátero (os três lados são
iguais); 2 - se formarem um triângulo isósceles (dois lados iguais e um
diferente); 3 - se formarem um triângulo escaleno (3 lados diferentes)*/


#include <stdio.h>
#include <locale.h>
#include <math.h>

float l1, l2, l3, l11, l22, l33, areaEsc, areaIso, areaEqui, perimetro; //variáveis necessárias
int pergunta, i;
int main(){

do {
	setlocale(LC_ALL, "");
	printf("Digite o valor do primeiro lado: \n");
	scanf("%f", &l11);
	printf("Digite o valor do segundo lado: \n");		//Informações Necessárias
	scanf("%f", &l22);
	printf("Digite o valor do terceiro lado: \n");
	scanf("%f", &l33);
	if(l11 > l22 && l11 > l33){
		l1 = l11;		
		l2 = l22;					//Organização de bases e lados
		l3 = l33;
		if(l1 >= (l2+l3) || l1 <= (l2-l3)){
			printf("Não existe triângulo!\n");		//verificação de existência de um triângulo
		} else {
			if(l1 != l2 && l1 != l3 && l3 != l2){
				float p, x;
				perimetro = l11 + l22 + l33;
				p = (l1 + l2 + l3) / 2;
				x = p * (p-l1) * (p-l2) * (p-l3);		//Triângulo escaleno
				areaEsc = sqrt(x);
				printf("Esse triângulo é escaleno! Sua área é: %.1f e seu perímetro é %.1f\n", areaEsc, perimetro);
			} else if(l1 == l2 && l2 != l3){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l3 / 2;
				alturaQuad = (l2 * l2) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l3 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			} else if(l1 == l3 && l3 != l2){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l2 / 2;
				alturaQuad = (l1 * l1) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l2 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso);
			} else if(l2 == l3 && l3 != l1){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l1 / 2;
				alturaQuad = (l2 * l2) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l1 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			}
		};
	}   else if (l22 > l11 && l22 > l33){
		l1 = l22;
		l2 = l11;			//Organização de bases e lados
		l3 = l33;
		if(l1 >= (l2+l3) || l1 <= (l2-l3)){
			printf("Não existe triângulo!\n");		//Verificador de existência do triângulo
		} else {
			if(l1 != l2 && l1 != l3 && l3 != l2){
				float p, x;
				perimetro = l11 + l22 + l33;
				p = (l1 + l2 + l3) / 2;
				x = p * (p-l1) * (p-l2) * (p-l3);			//Triângulo escaleno
				areaEsc = sqrt(x);
				printf("Esse triângulo é escaleno! Sua área é: %.1f e seu perímetro é %.1f\n", areaEsc, perimetro);
			} else if(l1 == l2 && l2 != l3){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l3 / 2;
				alturaQuad = (l2 * l2) - (c1 * c1); 		//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l3 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			} else if(l1 == l3 && l3 != l2){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l2 / 2;
				alturaQuad = (l1 * l1) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l2 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			} else if(l2 == l3 && l3 != l1){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l1 / 2;
				alturaQuad = (l2 * l2) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l1 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			}
		}
	} else if(l33 > l11 && l33 > l22){
		l1 = l33;
		l2 = l22;			//Organizador de lados e bases
		l3 = l11;
		if(l1 >= (l2+l3) || l1 <= (l2-l3)){
			printf("Não existe triângulo!\n");			//Verificador de existência do Triângulo
		} else{
			if(l1 != l2 && l1 != l3 && l3 != l2){
				float p, x;
				perimetro = l11 + l22 + l33;
				p = (l11 + l22 + l33) / 2;
				x = p * (p-l1) * (p-l2) * (p-l3);			//Triângulo escaleno
				areaEsc = sqrt(x);
				printf("Esse triângulo é escaleno! Sua área é: %.1f e seu perímetro é %.1f\n", areaEsc, perimetro);
			} else if(l1 == l2 && l2 != l3){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l3 / 2;
				alturaQuad = (l2 * l2) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l3 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			} else if(l1 == l3 && l3 != l2){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l2 / 2;
				alturaQuad = (l1 * l1) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l2 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			} else if(l2 == l3 && l3 != l1){
				float c1, aR, altura, alturaQuad;
				perimetro = l11 + l22 + l33;
				c1 = l1 / 2;
				alturaQuad = (l2 * l2) - (c1 * c1);			//Triângulo Isocele
				altura = sqrt(alturaQuad);
				areaIso = (l1 * altura) / 2;
				printf("Esse triângulo é isósceles! Sua área é: %.1f e seu perímetro é %.1f\n", areaIso, perimetro);
			}
		}
	} else if(l11 == l22 && l22 == l33){
				perimetro = l11 + l22 + l33;
				areaEqui = ((l11 * l11) * sqrt(3)) / 4;				//Triângulo Equilátero (caso único)
				printf("Esse triângulo é equilátero! Sua área é: %.1f e seu perímetro é %.1f\n", areaEqui, perimetro);
	};
	printf("Deseja calcular outro triângulo?\n");
	printf("Digite 1 para SIM, 2 para NÃO.\n");
	scanf("%d", &pergunta);
	if(pergunta == 1){
		i = i + 0;
	} else if (pergunta == 2){
		i = i + 5;
		printf("Ok! Encerrando Código!");
	} else {
		printf("Você digitou um valor diferente de 1 ou 2, portanto o código será encerrado.");
		i = i + 5;
	}
	}while (i != 5);
	return i;
}
