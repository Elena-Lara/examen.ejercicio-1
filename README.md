# examen.ejercicio-1

#include <stdio.h>
#include <stdlib.h>
void unaFuncion();void otraFuncion();

int variable;
main (){
   variable =9;
   printf ("El valor ee variable es: %i\n", variable);
   una funcion ();
   otra funcion ();
   printf ("ahora el valor de variable es: %i\n", variable);
   return;
}
void unaFuncion(){
   printf ("En la funcion unaFuncion, variable es: %i\n", variable);
}
void otraFuncion(){
   variable ++;
   printf ("En la funcion otraFuncion, variable es: %i\n", variable); return0;
}
