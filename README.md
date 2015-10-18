#include <stdio.h>


int main()
{
	int x;
	int y;
	printf("x = ");
	scanf("%d", &x);
	printf("y = ");
	scanf("%d", &y);

	if (x == 0 && y == 0)
	{
		printf("0.0");
	}
		else
		if (x == 0 && y < 0)
		{
			printf("-0x");
		}
		else
		if (x == 0 && y < 0)
		{
			printf("+0y");
		}
		else
		if (x < 0 && y == 0)
		{
			printf("-0x");
		}
		else
		if (x > 0 && y == 0)
		{
			printf("+0x");
		}
		else
		if (x < 0 && y > 0)
		{
			printf("2");
		}
		else
		if (x < 0 && y < 0)
		{
			printf("3");
		}
		else
		if (x > 0 && y > 0)
		{
			printf("1");
		}
		else
		if (x > 0 && y < 0)
		{
			printf("4");
		}
		else
		return 0;
}
