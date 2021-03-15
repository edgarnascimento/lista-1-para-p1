# lista-1-para-p1, questao 01

#include <stdio.h>
#include <stdlib.h>

int main(void) {

  int e_nro_1, e_nro_2, e_nro_3;

    printf("Digite o numero 1: ");
    scanf("%d", &e_nro_1);

      printf("Digite o numero 2: ");
      scanf("%d", &e_nro_2);

      printf("Digite o numero 3: ");
      scanf("%d", &e_nro_3);
      
      system("clear");

        if (e_nro_1>e_nro_2) {

          if (e_nro_1>e_nro_2) {
            printf("Digite o numero 3: %d\n",e_nro_3);
            printf("Digite o numero 2: %d\n",e_nro_2);
            printf("Digite o numero 1: %d",e_nro_1);
          } 

            else {
              
              if (e_nro_1>e_nro_3) {
                printf("Digite o numero 2: %d\n",e_nro_2);
                printf("Digite o numero 3: %d\n",e_nro_3);
                printf("Digite o numero 1: %d",e_nro_1);
              } 

              else {
                printf("Digite o numero 2: %d\n",e_nro_2);
                printf("Digite o numero 1: %d\n",e_nro_1);
                printf("Digite o numero 3: %d",e_nro_3);
              }
          }
        }

                else {

                  if (e_nro_1>e_nro_3) {
                    printf("Digite o numero 3: %d\n",e_nro_3);
                    printf("Digite o numero 1: %d\n",e_nro_1);
                    printf("Digite o numero 2: %d",e_nro_2);
                }

                    else{

                      if (e_nro_2>e_nro_3) {
                        printf("Digite o numero 1: %d\n",e_nro_1);
                        printf("Digite o numero 3: %d\n",e_nro_3);
                        printf("Digite o numero 2: %d",e_nro_2);

                    }

                        else {
                          printf("Digite o numero 1: %d\n",e_nro_1);
                          printf("Digite o numero 2: %d\n",e_nro_2);
                          printf("Digite o numero 3: %d",e_nro_3);
                        }
                    }
                }
  return 0;
}
