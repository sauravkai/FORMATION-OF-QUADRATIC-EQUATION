#include<stdio.h>
#include<math.h>

int main() 
{
float root1,root2,s,p;
printf("root1 = ");
scanf("%f", &root1);
printf("root2 = ");
scanf("%f", &root2);

s=(-1)*(root1+root2);
p=root1*root2;

printf("x*2 + %fx + %f = 0",s,p);

return 0;
}
