#include <stdio.h>

int main()
{
    while(1){

    int i, n, fact=1;
    printf("Enter any number: ");
    scanf("%d", &n);

    for(i=1; i<=n; i++){
        fact=fact*i;
    }
    printf("%d\n", fact);

    }
    return 0;
}
