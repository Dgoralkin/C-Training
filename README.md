#include <stdio.h>
#include <cs50.h>

int main(void)
{
    string name = get_string("What is your name? \n");
    printf("Hello, %s.\n", name);
    int age = get_int("And what is your age %s ?\n", name);
    printf("So, your name is %s, and you are %i years old.\n", name, age);
    int counter = 0;
    printf("If so, next year, you are going to be %i.\n", age + 1);
    string yn = get_string("Right? (Y/N)?");
}
