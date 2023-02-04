# -
个人代码学习
#include<stdio.h>
int main()
{
	int i = 0;
	do
	{
		printf("%d\n", i);
		i++;
	}
	while (i < 10);

	return 0;
	
 }//do while 语句的应用
//#include<stdio.h>
//int main()
//{
//	int i = 0;
//	int j = 0;
//	for (; i < 10; i++)
//	{
//		for (; j < 10; j++)  //J未清除，仍未10,因此直接跳过，只打印十次i=0的时候
//		{
//			printf("hehe\n");
//		}
//
//	}
//	return 0;
//}
//#include<stdio.h>
//int main()
//{
//	for (; ; )
//		printf("hehe\n");
//	return 0;
//for循环的初始，判断，调整均可以省略，省略后均为真
//#include<stdio.h>
//int main()
//{
//	int i = 0;
//	for (i = 0; i <= 13; i++)
//	{
//		if(i=4)
//		printf("haha\n");
//	}
//
//	return 0;
//不可以在for循环中，修改循环变量，防止for循环失去控制

//#include<stdio.h>
//int main()
//{
//	int i = 0;
//	for (i = 1; i <= 7; i++)
//	{
//		printf("%d", i);
//	}
//	return 0;
//}
////for循环的使用
