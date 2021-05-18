# 1
int main()
{
	int i = 0;
	int j = 0;
	int c= 0;//35
	int d = 0;//94
	scanf("%d %d", &c, &d);
		
	for (i = 0; i <= c; i++)
	{
		j = c - i;
		if (i * 2 + 4 * j == d)
		{
			printf("鸡的数量为：%d\n兔的数量为：%d\n", i, j);
		}

		
	}
	return 0;
}
