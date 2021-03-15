# lista-1-para-p1
#include <stdio.h>

int main(void) {
  int Resistor_1, Resistor_2, Resistor_3, Resistor_4, Resistor_Equivalente;

 printf("Entre com o valor do Resistor 1: ");
 scanf("%i", &Resistor_1);

printf("Entre com o valor do Resistor 2: ");
scanf("%i", &Resistor_2);

printf("Entre com o valor do Resistor 3: ");
scanf("%i", &Resistor_3);

printf("Entre com o valor do Resistor 4: ");
scanf("%i",&Resistor_4);

Resistor_Equivalente = Resistor_1 + Resistor_2 + Resistor_3 + Resistor_4;

printf("Resultado da soma dos resistores: %.2i ", Resistor_Equivalente);


  return 0;
}
