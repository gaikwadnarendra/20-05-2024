// Online C compiler to run C program online
#include <stdio.h>

int main() {
   int amount,a,b,c,d,e,f,g,h,i,j;
   
   printf("Enter the amount:");
   scanf("%d",&amount);
   j=amount;
   
   while(amount>0)
   {
       a=amount/500;
       amount=amount%500;
       printf("Notes of:500 * %d=%d\n",a,(500*a));
       b=amount/200;
       amount=amount%200;
       printf("Notes of:200 * %d=%d\n",b,(200*b));
       c=amount/100;
       amount=amount%100;
       printf("Notes of:100 * %d=%d\n",c,(100*c));
       d=amount/50;
       amount=amount%50;
       printf("Notes of:50 * %d=%d\n",d,(50*d));
       e=amount/20;
       amount=amount%20;
       printf("Notes of:20 * %d=%d\n",e,(20*e));
       f=amount/10;
       amount=amount%10;
       printf("Notes of:10 * %d=%d\n",f,(10*f));
       g=amount/5;
       amount=amount%5;
       printf("Notes of:5 * %d=%d\n",g,(5*g));
       h=amount/2;
       amount=amount%2;
       printf("Notes of:2 * %d=%d\n",h,(2*h));
       i=amount/1;
       amount=amount%1;
       printf("Notes of:1 * %d=%d\n",i,(1*i));
       printf("Total Amount:%d",j);
       
   }
}