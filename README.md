#include<stdio.h>
#include<conio.h>
int main ()
{
char str[30];
    int length;
    int i;
    int count;
    printf("Enter the string\n");
    gets(str);
    length=strlen(str);
    for(i=0;str[i]!='\0';i++)
    {
        if(!(str[i]==' '))
        {
            count++;
        }
    }
    printf("%d",count);
    }
getch();
return 0;
}
