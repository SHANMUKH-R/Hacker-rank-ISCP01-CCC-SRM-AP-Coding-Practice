#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main()
{
    int N,sp,i;
    scanf("%d%d",&sp,&N);
    int a[N]; //for storing opponents strength
   
    for(i=0;i<N;i++)
    {
        scanf("%d",&a[i]);
        if(sp<=a[i])
        {
            printf("-1");//Pokeman never win the battle
            return 0;
        }
    }
        int day=1;
        int x=sp;
        /*
        10
        7
        1 2 4 7 2 5 5 */
   
        for(i=0;i<N;)//Opponent strength is less than pokeman
        {
            if(a[i]<x)//Battle going
            {
                x=x-a[i];//defeated a[i] person  ==>10-1=9,9-2=7,7-4=3
                i++;//takes next person for battle
            }
            else//Take rest and poke recharge again
            {
                day++;
                x=sp;
            }
               
        }
    printf("%d",day);  
   
   
    return 0;
}
