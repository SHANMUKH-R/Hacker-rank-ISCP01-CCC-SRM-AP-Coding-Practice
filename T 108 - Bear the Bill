#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */ 
    
    char str[1000000];
    while(gets(str))
    {
        double I=0,V=0,R=0;
        char b[10000];
        int i=0,k,j;
        while(str[i])
        {
            if(str[i]=='=')
            {
                    k=1;
                    for(j=0;j<10;j++)
                    {
                        b[j]=str[i+k];
                        k++;
                    }
                if(str[i-1]=='I')
                    I=atoi(b);
                if(str[i-1]=='V')
                    V=atoi(b);
                if(str[i-1]=='R')
                    R=atoi(b);
            }
            i++;
        }
    
if(I&&V)
     {
         R=V/I;
         printf("R=%.2lfO",R);
         
     }
     else if(R&&V)
     {
         I=V/R;
         printf("I=%.2lfA",I);
     }
     else if(I&&R)
     {
         V=I*R;
         printf("V=%.2lfV",V);
         
     }
        printf("\n");
     

        
    }
  
    return 0;
}
