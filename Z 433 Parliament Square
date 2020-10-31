#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long int n,m,a,ans;
    scanf("%lld" "%lld" "%lld", &n, &m, &a);
    if(a>n && a>m){
        return 1;
    }
    else{  
        if(n%a>0)
            n = (n/a)+1;  
        else
            n = (n/a);  
        if(m%a>0)
            m = (m/a)+1;  
        else
            m = (m/a);  
        ans = n*m;  
        printf("%lld", ans);
    }
}
