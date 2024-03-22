/*Escreva um algoritmo que leia os valores das quatro provas de um aluno e
escreva a média aritmética considerando apenas as três melhores notas. Por
exemplo, se os valores lidos foram 9, 9.5, 7, e 8, a média será (9 + 9.5 + 8)/3 (a
prova de nota 7 é descartada). Dica: Não esqueça de considerar a
possibilidade de ocorrerem notas iguais.*/

#include <stdio.h>

int main(){
	float p1, p2, p3, p4, media;
	printf("Digite o valor da primeira prova: \n");
	scanf("%f", &p1);
	printf("Digite o valor da segunda prova: \n");
	scanf("%f", &p2);
	printf("Digite o valor da terceira prova: \n");
	scanf("%f", &p3);
	printf("Digite o valor da quarta prova: \n");
	scanf("%f", &p4);
	if(p1 < p2 && p1 < p3 && p1 < p4){
		media = (p2 + p3 + p4)/3;
		printf("A sua media sem a primeira prova: %0.1f", media);
	} else if(p2 < p1 && p2 < p3 && p2 < p4){
		media = (p1 + p3 + p4)/3;
		printf("A sua media sem a segunda prova: %0.1f", media);
	} else if(p3 < p1 && p3 < p2 && p3 < p4){
		media = (p1 + p2 + p4)/3;
		printf("A sua media sem a terceira prova: %0.1f", media);
	} else if(p4 < p1 && p4 < p2 && p4 < p3){
		media = (p1 + p3 + p2)/3;
		printf("A sua media sem a quarta prova: %0.1f", media);
	}
}
