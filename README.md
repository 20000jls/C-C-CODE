# C/C++ CODE
Never give up
//分支语句和循环语句
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	int age = 10;
	if (age < 18)
		printf("未成年\n");
	else if (age >= 18 && age < 28)//此处不可写成 if(18<=age<28); 在第一步10<18，正确，为0,0<28,也为真，输出显示青年
		printf("青年\n");
	return 0;
	
}
hfh
