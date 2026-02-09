C Programming Practical File
This repository contains basic C language programs written for academic practicals and examinations. All programs are simple, menu-free, and beginner friendly.

Program 1: Temperature Converter (Celsius to Fahrenheit)
Aim:
To write a C program that converts temperature from Celsius to Fahrenheit.

Formula:
F = (9 / 5 × C) + 32

Input:
Temperature in Celsius (user input)
Output:
Temperature in Fahrenheit
Source Code:
#include <stdio.h>

int main()
{
    float c, f;

    printf("Enter temperature in Celsius: ");
    scanf("%f", &c);

    f = (9.0 / 5.0) * c + 32;

    printf("Temperature in Fahrenheit = %.2f", f);

    return 0;
}
