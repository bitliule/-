#define _CRT_SECURE_NO_DEPRECATE
#include <stdio.h>
#include <stdlib.h>
koujue(int n)
{
	int i = 0;
	int j = 0;
	for (i = 1; i <= n; i++)
	{
		for (j = 1; j <= i; j++)
		{
			printf("%d*%d=%-2d ", i, j, i*j);
		}
		printf("\n");
	}
}
int main()
{
	int line = 0;
	printf("请输入乘法口诀表的行列数\n");
	scanf("%d", &line);
	koujue(line);
	system("pause");
	return 0;
}
