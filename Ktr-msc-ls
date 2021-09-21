#include <stdio.h>
#include <stdlib.h>
void main() {
    char nom[20];
    char prenom[20];
    char mail[80];
    int numero;
        int motdepasse=1234;
        int reponse; 
        int rep=1;
        do
              {
                  fflush(stdin);
                  
            printf ("Entrer un mot de passe \n");
            scanf("%d", &reponse);
            if (reponse==motdepasse){
               
              
                  
              fflush(stdin);
                printf ("Entrer le nom\n");
                gets(nom);
                printf ("Entrer le prenom\n");
                 gets(prenom);
                printf ("Entrer votre adresse mail\n");
                 gets(mail);
                printf ("Entrer votre numero \n");
                scanf("%d", &numero);
                        FILE*f = NULL;
    
                        f = fopen("hassantest.txt", "a");
                        fprintf (f,"%s;%s;%s;%d", nom, prenom, mail, numero);
                        fclose(f);
                         printf ("données enregistrer avec succès \n");
                         printf ("voulez vous mettre un autre donner si OUI taper 1 SINON 0\n");
                         scanf("%d",&rep);
                    
             }   
     
    
     else { 
         printf ("mot de passe incorrect \n");
     }
        } while (rep==0);
}
