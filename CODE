#include <stdio.h>
#include <stdlib.h>
#include<time.h>

int main()
{
  int numero,somme,n,continuer_partie=1,i;
  int continuerpartie=1;
  int argent = 1000;
   srand(time(NULL));

       printf("        ************************************************************************\n");
       printf("                           ** :) WELCOME TO CASINO GAME :) **\n") ;
       printf("        **************************************************************************\n");
       printf("\n\n\t\t      =============================");
	printf("\n\t\t      ||\t\t\t ||");
    printf("\n\t\t      ||\t\t\t ||");
	printf("\n\t\t      ||");

	printf("      MADE BY : NOUHAILA PRO       \t ");
	printf("\n\t\t      ||\t\t\t ||");
	printf("\n\t\t      ||\t\t\t ||");
	printf("\n\t\t      =============================\n\n\n");

       while(continuerpartie==1){

        printf("vous installez a la table de roullete avec \n\n",argent);
        printf("  misez sur un numero entre 0 et 49 : \n");
        scanf("%d",&numero);

        while (numero>49 || numero <0 ){
            printf("numero invalide\n");
            printf("remiser sur un numero entre O et 49 : \n\n");
            scanf("%d",&numero);
         }


         printf("deposez la somme que vous souhaitez misez \n");
         scanf("%d",&somme);
         while(somme>argent){
            printf("argent invalide\n");
            printf("déposer une somme valide");
            scanf("%d",&somme);
        }
        n=rand()%49;
        printf("la roulette tourne .");

        for(i=0;i<20;i++){
            printf(".");
            sleep(1);
        }
        printf("et s'arrete sur %d \n", n);


        if(numero==n){
              printf("vous avez gagné %d \n",somme*3);
             argent+=somme*3;
              printf("vous avez maintenant : %d \n ",argent);

        }
        else if (numero%2==n%2){
            printf("vous avez misez sur la bonne couleur \n",somme/2);
            argent-=somme/2;
            printf("vous avez maintenant:%d \n",argent);

        }
        else {
               printf("desole c'est pas pour cette fois \n ");
              argent-=somme;
               printf("vous avez maintenant %d \n ",argent);
        }

           printf(" voullez vous jouer une autre fois ou bien quitter\n ");
           printf(" 1 - jouer une autre fois \n");
           printf(" 2 - quitter \n   ");
           scanf("%d",&continuerpartie);
           }


           }
