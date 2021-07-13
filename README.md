#include<stdio.h>
#include<string.h>
struct date
{
    int dd;
    int mm;
    int yyyy;
};
struct employee
{
    int id;
    char name[30];
    struct date doj;
};
int main()
{
    struct employee e;
    e.id=220;
    strcpy(e.name,"DIVYA");
    e.doj.dd=22;
    e.doj.mm=12;
    e.doj.yyyy=2021;
    printf("\n %d \n",e.id);
    printf("\n %s \n",e.name);
    printf("\n %d \n",e.doj.dd);
    printf("\n %d \n",e.doj.mm);
    printf("\n %d \n",e.doj.yyyy);
    return 0;
}
