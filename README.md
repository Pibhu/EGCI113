# EGCI113
#include <stdio.h>
#include <math.h>

int main()
{
    int a,b,c;
  
    printf("a=");
    scanf("%d",&a);
    printf("b=");
    scanf("%d",&b);
    printf("c=");
    scanf("%d",&c);
    
    float x1,x2;
    x1=(-b+sqrt((pow(b,2))-(4*a*c)))/(2*a);
    x2=(-b-sqrt((pow(b,2))-(4*a*c)))/(2*a);
    
    printf("x1=%.2f,x2=%.2f",x1,x2);

    return 0;
}
