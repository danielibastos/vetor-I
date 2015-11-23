# vetor-I

#include<stdio.h>
 
int main(){
    float X=0, Z=0;
    int A[100], i=0;
    //for para rodar as posicoes do vetor 
    for(Z=0;Z<100;Z++){
    //armazenar os numeros digitados        
            scanf("%f", &X);
    //atribuir as posicoes do vetor     
            A[i] = Z;
    //armazenar os numeros digitados em X recebe X      
            X=X;
    // decisao em que os numeros digitados so sao mostrados ate 10      
            if(X<=10){
printf("A[%d] = %.1f\n", A[i], X);}
}
    return 0;
}
