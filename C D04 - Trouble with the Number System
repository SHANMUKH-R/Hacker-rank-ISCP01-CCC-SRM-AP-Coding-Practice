#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int n, count = 0;
    scanf("%d", &n);
    long long int x, product = 1;
    for (int i = 0; i < n; i++) {
        scanf("%lld", &x);
        while(1) {
            if (x % 10 == 0) {
                count++;
                x /= 10;
            }
            else {
                if (x != 1) {
                    product *= x;
                }
                break;
            }
        }
    }
    printf("%lld", product);
    for (int i = 0; i < count; i++) {
        printf("0");
    }
}
