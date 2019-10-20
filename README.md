# Zhang-h-d
#c语言笔记

    第一项：写程序时记得写注释（符号为//）
    第二项：对于各种符号要记清，如："%s"代表字符串，"%c"代表单个字符
    第三项：记得将变量初始化
    第四项：记得优先级顺序，算术运算符第一，关系运算符第二，赋值运算符第三
    第五项：c语言中所有非零整数都理解为true
    第六项：_和字母开头才是正确的标识符
    第七项：while后要加{}，否则可能陷入死循环
    第八项：输入要取址，如：scanf("%d\n",&x),&不能忘
    第九项：for语句嵌套一般用于一个控制行，一个控制列

##第一个自我编写成功的程序
    #include<stdio.h>
    int main()
    {
    int results;
    char x=‘A’,y=‘B’,a=‘C’,b=‘D’,e=‘E’;
    printf(“输入一个学生的成绩”);
    scanf("%d\n",&results);
    if(results>=90)
    {
    printf("%c\n",x);
    }
    else if(results>=80)
    {
    printf("%c\n",y);
    }
    else if(results>=70)
    {
    printf("%c\n",a);
    }
    else if(results>=60)
    {
    printf("%c\n",b);
    }
    else
    {
    printf("%c\n",e);
    }
    return 0;
    }
###学习链接
[markdown教程](https://www.runoob.com/markdown/md-link.html）
————————————————
版权声明：本文为CSDN博主「Jackylove_」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/Jackylove_/article/details/102074905
