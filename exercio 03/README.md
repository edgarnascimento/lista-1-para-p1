# lista-1-para-p1
#include <stdio.h>

int main(void) {

  int var_A, var_B ,var_Aux;

  printf("Entre com o valor de var_A \n");
  scanf("%i", &var_A);

  printf("Entre com o valor de var_B \n");
  scanf("%i", &var_B);

  var_Aux = var_A;
  var_A = var_B;
  var_B = var_Aux;

  printf("var A: %i  var B: %i \n", var_A, var_B);

  return 0;
}
