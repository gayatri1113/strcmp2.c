//# strcmp2.c//
#include<stdio.h>
#include<string.h>
int main()
{
    char a[20],b[20];
    printf("Enter first string:");
    scanf("%s",&a);
    printf("Enter second string:");
    scanf("%s",&b);
    if(strcmp(a,b)==0)
    {
        printf("Equal.");
    }
    else
    {
        printf("Not equal.");
    }
    return 0;
}
