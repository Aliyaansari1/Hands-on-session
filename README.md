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
int main()
{
int i, temp, j;
 int a[]={4,2,6};
for(i=0;i<3; i++)
{
for(j=i+1; j<3; j++)
{
if(a[i]<a[j])
{
temp=a[i];
a[i]=a[j];
a[j]=temp;
}
}
}
for(i=0; i<3; i++)
{
    printf("%d\n", a[i]);
 }
    
    }
    