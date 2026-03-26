# pz9
<img width="1036" height="352" alt="image" src="https://github.com/user-attachments/assets/67b0dd7c-9b3d-4fe7-985e-37f9a47851a8" />

Ex1
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    switch (n) {
    case 1: cout << " Один"; break;
    case 2: cout << "Два"; break;
    case 3: cout << "Три"; break;
    default: cout << "Ошибка"; 
}

    // Ваш код:


    return 0;
}
```
Ex2
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    switch (n) {
    case 1: cout << "Понедельник"; break;
    case 2: cout << "Вторник"; break;
    case 3: cout << "Среда"; break;
    case 4: cout << "Четверг"; break;
    case 5: cout << "Пятница"; break;
    case 6: cout << "Суббота"; break;
    case 7: cout << "Воскресенье"; break;        
    default: cout << "Неверный день"; 
}
    

    // Ваш код:


    return 0;
}
```
Ex3
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    switch (n) {
    case 1: cout << "Зима"; break;
    case 2: cout << "Зима"; break;
    case 3: cout << "Зима"; break;
    case 4: cout << "Весна"; break;
    case 5: cout << "Весна"; break;
    case 6: cout << "Весна"; break;
    case 7: cout << "Лето"; break;
    case 8: cout << "Лето"; break;
    case 9: cout << "Лето"; break;
    case 10: cout << "Осень"; break;
    case 11: cout << "Осень"; break;
    case 12: cout << "Осень"; break;
        
    default: cout << "Ошибка"; 
}


    // Ваш код:


    return 0;
}
```
Ex4
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    char op;
    int a, b;
    cin >> op >> a >> b;

    if (op == '+') {
        cout << a + b;
    } else if (op == '-') {
        cout << a - b;
    } else if (op == '*') {
        cout << a * b;
    } else if (op == '/') {
        if (b == 0) {
            cout << "Деление на ноль";
        } else {
            cout << a / b;
        }
    } else {
        cout << "Ошибка";
    }

    return 0;
}

```
Ex5
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    switch (n) {
    case 1: cout << "Плохо"; break;
    case 2: cout << "Плохо"; break;
    case 3: cout << "Удовлетворительно"; break;
    case 4: cout << "Хорошо"; break;
    case 5: cout << "Отлично"; break;        
    default: cout << "Ошибка"; 
}

    // Ваш код:


    return 0;
}
```
Ex6
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;
    switch (n) {
    case 0: cout << "Ноль"; break;        
    case 1: cout << "Один"; break;
    case 2: cout << "Два"; break;
    case 3: cout << "Три"; break;
    case 4: cout << "Четыре"; break;
    case 5: cout << "Пять"; break;
    case 6: cout << "Шесть"; break;
    case 7: cout << "Семь"; break;
    case 8: cout << "Восемь"; break;
    case 9: cout << "Девять"; break;
    
    default: cout << "Ошибка"; 
}


    // Ваш код:


    return 0;
}
```
Ex7
```
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int a, b;
    int op;
    cin >> a >> b >> op;

    if (op == 1) {
        cout << a + b;
    } else if (op == 2) {
        cout << a - b;
    } else if (op == 3) {
        cout << a * b;
    } else if (op == 4) {
        if (b == 0) {
            cout << "Деление на ноль";
        } else {
            cout << a / b;
        }
    } else {
        cout << "Ошибка";
    }

    return 0;
}

```
