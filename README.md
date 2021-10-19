#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main()
{
int a=1;
int b;
while (a < 100)
{


	b = 2*a + 2;
	a = a + 2;
	printf("和为： % d\n", b);
}
printf("%d", a);
return 0;
}
