#include <stdio.h>
int main() {
    
      //estrtutura for (torre)
  printf ("movimento da torrre\n");
      for ( int t = 0; t < 2; t++) {
   printf ("direita\n"); // duas casas para a direita 
 }
    // estrutura while (bispo)
    printf("\n");
  printf ("movimento do bispo\n");
         int b = 0; 
      while (b <= 3) {
       b++;
    printf ("diagonal cima esquerda\n"); // quatro casas para a diagonal esquerda 
    }
       // estrtutura do-while (rainha)
     printf("\n");
  printf ("movimento da rainha\n");
    int r = 0; 
       do {
    printf ("esquerda\n"); // uma casa para a esquerda 
           r++;
     } while (r <= 1); 
   
    // estrtura de repetição aninhados (for)
    printf ("\n");
 printf ("movimento do cavalo\n");
        for (int c = 1; c <= 1; c++) { 
           printf ("%d\t", c );
      printf ("\n");
      printf ("cima\n");
      printf ("cima\n");
      printf ("esquerda\n");
        }
    

    return 0;
}
