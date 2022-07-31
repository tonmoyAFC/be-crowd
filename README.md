# be-crowd
#include <stdio.h>

int main() {
    float n;
    scanf("%f",&n);
    
    if (n<0 || n>100){
        printf("Fora de intervalo\n",n);
    }
    else{
        if (n> 0 && n<=25){
            printf("Intervalo [0,25]\n",n);
        }
        
        else if(n>25 && n<=50){
            printf("Intervalo [0,25]\n",n);
        }
        
        else if(n>50 && n<75){
            printf("Intervalo [50,75]\n",n);
        }
        else{
            printf("Intervalo (75,100]\n",n);
        }
        
    }
    
    return 0;
}
