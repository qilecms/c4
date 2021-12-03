# c4编译器中文注释版



c4 - C 中的四个函数
极简主义的练习。

请尝试以下操作：

gcc -o c4 c4.c
./c4 hello.c
./c4 -s hello.c

./c4 c4.c hello.c
./c4 c4.c c4.c hello.c

#示例代码

#include <stdio.h>

int main()
{

    int i;
	int j;
	i=0;
	while(1)
	{
		if(i < 10){
		 	printf("hello, world%d\n",i);
		}else{
		   j = i/2;
		    printf("task%d\n",j);
		}
	    i++;
	}
	return 0;
}

