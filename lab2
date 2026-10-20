#include <iostream>
#include <cmath> // підключення бібліотеки математичних функцій

using namespace std;

int main()
{
    // Завдання Integer21
    // З початку доби минуло N секунд.
    // Знайти кількість секунд, що пройшли з початку останньої хвилини.
    int N;
    int seconds;

    cout << "===== Завдання Integer21 =====" << endl;
    cout << "Введіть кількість секунд N: ";
    cin >> N;

    seconds = N % 60;

    cout << "Кількість секунд з початку останньої хвилини = "
         << seconds << endl;

    // Завдання Boolean9
    // Дано два цілих числа A і B.
    // Перевірити: "Хоча б одне з чисел A і B непарне".
    int A;
    int B;
    bool isOdd;

    cout << endl;
    cout << "===== Завдання Boolean9 =====" << endl;
    cout << "Введіть число A: ";
    cin >> A;
    cout << "Введіть число B: ";
    cin >> B;

    isOdd = (A % 2 != 0) || (B % 2 != 0);

    cout << "Хоча б одне число непарне: "
         << boolalpha << isOdd << endl;

    // Завдання Math34
    // Обчислити математичний вираз:
    // y = 3*pi*sin^3(pi+2*x)*cbrt(|x-0.5*e^x|)
    //     / (3^(x-5)*log(sin(37 degrees))).
    const double pi = 3.141592;
    double x;
    double y;
    double angle37;
    double numerator;
    double denominator;

    cout << endl;
    cout << "===== Завдання Math34 =====" << endl;
    cout << "Введіть дійсний аргумент x: ";
    cin >> x;

    // Переведення кута 37 градусів у радіани.
    angle37 = 37 * pi / 180;

    // Обчислення чисельника.
    numerator = 3 * pi
        * pow(sin(pi + 2 * x), 3)
        * cbrt(fabs(x - 0.5 * exp(x)));

    // Обчислення знаменника.
    denominator = pow(3, x - 5)
        * log(sin(angle37));

    y = numerator / denominator;

    cout << "Значення функції y = " << y << endl;

    return 0;
}
