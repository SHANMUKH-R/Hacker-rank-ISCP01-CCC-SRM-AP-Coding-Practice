#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main()
{
    int n,r,i=0;
    scanf("%d",&n);//n=704  o/p==>AAB
    char s[10];
    while(n>0)
    {
        r=65+(n-1)%26;//65+(703)%26==> 65+1=66, 65+0, 65+0
        n=(n-1)/26;//704-1==>703/26==>27, 
        s[i]=r;//s[0]=66,s[1]=65, s[2]=65
        i++;
    }
    s[i]='\0';
    for(int i=strlen(s)-1;i>=0;i--)
        printf("%c",s[i]);//AAB
    return 0;
    
}
