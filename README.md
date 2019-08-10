#include<stdio.h>
int main()
{
int X,sum;
long int P;
scanf("%d %lld",X,P);
while(sum!=0)
{
sum=X-((P*X)/100);
print("%d\n",sum);
}
if(sum==0)
printf("FREE");
return 0;
}


