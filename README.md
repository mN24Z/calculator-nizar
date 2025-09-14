# calculator-nizar
my first project calculator in c language  
#include<stdio.h>
 
int main(){
    int a , b;
    char c ;

     printf("enter the first num :");
     
         scanf("%d",&a);

    printf("enter the second num :");

         scanf("%d",&b);
         
    printf("ente the sign :");

         scanf(" %c",&c);
 
     if(c == '+'){
        printf("the resul is : %d",a + b);
     }
     else if ( c == '-')
     {
        printf("the result is : %d",a- b);
     }
     else if (c == '*')
     {
        printf(" the result is : %d",a *b);
     }
     else if (c == '/')
     {
        printf("the result is :%d", a/b);
         if (b != 0)
         {
            printf("the result is :%d", a/b);
         }
            else{
                printf("Error:cannot devide");
            }
         }
         else{
            printf("ERROR: :(");
         }
         return 0;
     }
