//c program to swap two numbers without using temporary variable.
#include<stdio.h>
int main()
{
int a, b;
printf("Enter the value of a \n");
scanf("%d",&a);
printf("Enter the value of b\n");
scanf("%d",&b);
printf("Values of a and b before swapping are : %d,%d\n",a,b);
//swapping starts from here 
a=a+b;
b=a-b;
a=a-b;
printf("Values of a and b after swapping are : %d,%d\n",a,b);
return 0;
}
