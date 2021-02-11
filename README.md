#include<studio.h>
Int main()
{
int a,b,c;
printf("enter a,b");
scanf("%d%d",&a,&b);
c=a;
a=b;
b=c;
printf("a=%d\nb=%d",a,b);
return 0;
}
