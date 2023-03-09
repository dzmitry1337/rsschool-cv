# *rsschool-cv*

***Loseu Dzmitry***

## **Contacts**

+ **Discord:** Ryadovoy Pudge #8832 (private messaging account)
+ **Discord:** Ryadovoy_Rudgers1337 #8506
+ **Email:** ryadovoy_pudge@mail.ru

## **About Me**

I have different personality traits. I'm good in communication, for this reason I like to work in a team. I have a responsible attitude to work and study.

## **Skills**

+ C++ (Basics)
+ Git (Basics)
+ HTML (Basics)

## **Code example**

#include <stdlib.h>
#include <stdio.h>
#include <locale.h>
#include <math.h>
double max(double x,double y);
double min(double x,double y);
void chek(double a, double b);
int main()
{
    setlocale(LC_ALL, "Russian");
    printf_s("Введите переменные x и y \n");
    double x, y;
    scanf_s("%lf %lf", &x, &y);
    int a = 0;
    chek(x, y);
    return 0;
}
void chek(double a, double b)
{
    bool t = 1;
    while (t)
    {
        int x = scanf_s("%lf %lf", &a, &b);
        if (x != 2)
        {
            printf_s("Вы ввели не число или не 2 числа, введите ещё раз 2 числа \n");
            //fflush(stdin);
            scanf_s("%lf %lf", &a, &b);
            x = scanf_s("%lf %lf", &a, &b);
            t = 0;
        }
        else break;
    }
}
    double max(double x, double y)
    {
        if (x > y)
        return x;
        else return y;
    }
    double min(double x, double y)
    {
        if (x < y)
        return x;
        else return y;
    }

## **Projects**
+ That's my first [project](https://dzmitry1337.github.io/rsschool-cv/)

## **Education**

+ **University:** Belarusian State University of Informatics and Radioelectronics (still studying)

## **Languages**
+ **English:** A2. My only practice in English was watching films and movies with subtitles.
+ **Russian:** Native speaker.
+ **Belarusian:** Native speaker.