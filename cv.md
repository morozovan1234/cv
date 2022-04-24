# Anastasia Morozova
## Student of VSU named after P.M.Masherov
### Contact information:
**Phone:** +375298195778

**E-mail:** nastya.morozova.756393@mail.ru

**Second E-mail:** nastya.15.mor@mail.ru

**Telegram:** @m_nst
### Briefly About Myself
In 2021, I entered the Vitebsk State University named after P. M. Masherov, majoring in information resource management. Here we specialize in programming and economics mainly. To enter this specialty, it was necessary to pass a centralized test in Russian (or Belarusian) language, mathematics and foreign language. In this regard, I studied mathematics and English at an advanced level. In mathematics, I attended additional classes at school. I studied English in additional classes at school, courses at school and also went to a tutor. 

During the year of study at the university, I was very interested in computer graphics and programming. Although it is not very easy, but the main thing is the desire to learn new things and patience

In my freetime I try to learn something new related to programming, computer graphics and just self-development, therefore, I believe that my desire to learn new things and determination will help to achieve a lot in these areas of activity.
### Skills and Proficiency:
- C++, Assembler
- HTML
- Adobe Photoshop, illustrator
### Code example:
Condition: *Given an array of N real numbers. Write a program to find in this array the sum of the array elements located between the first and second negative elements.*
```
#include <iostream>
#include <math.h>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");
    double a;
    double sum = 0;
    int n;
    int step = 0;
    cout << "Введите размер массива: ";
    cin >> n;
    cout << "Введите элементы массива: " << endl;
    for (int j = 0; j < n; j++)
    {
        cin >> a;
        switch (step)
        {
        case 0:
            if (a < 0)
                step = 1;
            break;
        case 1:
            if (a < 0)
                step = 2;
            else
                sum += a;
            break;
        case 2:
            break;
        }
    }
    switch (step)
    {
    case 0:
        cout << "Нет отрицательных элементов" << endl;
        break;
    case 1:
        cout << "Есть только один отрицательный элемент" << endl;
        break;
    case 2:
        cout << "Сумма =  " << sum << endl;
    }
    return 0;
}
```
### Languages:
* English - Pre-intermidiate
