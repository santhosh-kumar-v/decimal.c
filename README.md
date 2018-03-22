#include<stdio.h>
int main()  
{
   int n,b,a[1000],k=0,j;
   scanf("%d%d",&n,&b);
   while(n>0)
   {
       a[k++]=n%b;
       n=n/b;
   }
   for(j=k-1;j>=0;j--)
   {
       printf("%d",a[j]);
   }
}
