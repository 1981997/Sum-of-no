#include<stdio.h>
main()
{
int sum,count,n;
printf("Enter n'th natural no:-");
scanf("%d",&n);
for(count=1;count<=n;count++)
{
sum=sum+count;
}
printf("sum of %d natural no is :- %d",n,sum);
getch();
}
