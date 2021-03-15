# lista-1-para-p1
#include <stdio.h>

int main(void) {
  float Resistor_1, Resistor_2, Resistor_3, Resistor_4, Resistor_1e2, Resistor_3e4, Resistor_Equivalente;

 printf("Entre com o valor do Resistor 1: ");
 scanf("%f", &Resistor_1);

printf("Entre com o valor do Resistor 2: ");
scanf("%f", &Resistor_2);

printf("Entre com o valor do Resistor 3: ");
scanf("%f", &Resistor_3);

printf("Entre com o valor do Resistor 4: ");
scanf("%f",&Resistor_4);

Resistor_1e2 = (Resistor_1 * Resistor_2)  /  (Resistor_1 + Resistor_2);

printf("Resultado da soma dos resistores: %.2f\n ", Resistor_1e2);

Resistor_3e4 = (Resistor_3 * Resistor_4)  /  (Resistor_3 + Resistor_4);

printf("Resultado da soma dos resistores: %.2f\n ", Resistor_3e4);

Resistor_Equivalente = (Resistor_1e2 * Resistor_3e4) / (Resistor_1e2 + Resistor_3e4);

printf("Resultado da soma dos resistores: %.2f\n ", Resistor_Equivalente);


  return 0;
}
