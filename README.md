# code room
#include <stdio.h>

int main() 
{
    int i,j;
    for(i=1;i<=3;i++)
    {
        for(j=1;j<=i;j++)
        {
            printf("* ");
        }
        printf("\n");
    }
    for(i=3;i>=0;i--)
    {
        for(j=0;j<=i;j++)
        {
            printf("* ");
        }
        printf("\n");
    }
    
    
    return 0;
}
