#include <stdio.h>
#include <cs50.h>

int main(void)
{
    //This is readable zone;
    int x = get_int("X:?\n");
    int y = get_int("Y:?\n");
    //Z example
    //    int z = x+y;
    //    printf("The sum of %f+%f is %f\n",x, y, z);
    if (x > y)
    {
        printf("X is bigger than Y.\n");
    }
    else if (x < y)
    {
        printf("X is smaller than Y.\n");
    }
    else (x = y);
    {
        printf("X is eaqual to Y.\n");
    }
}
