Задача 3. Простейший калькулятор
Написать программу, выполняющую операции над числами. Программа принимает в себя
арифметическое выражение в постфиксной нотации: последовательность чисел и операторов
действий над двумя последними числами.

Например, входная последовательность 5 10 + означает: 5 + 10.

5 10 + 10 * означает (5 + 10) * 10.
5 10 15 + - означает 5 - (10 + 15).

Числа во входной последовательности гарантированно целые. Допустимые операторы: +

(сложение), - (вычитание), * (умножение), / (деление).

Операторы и числа во входной последовательности отделены друг от друга пробелом.

Входная последовательность операторов и чисел гарантированно даёт целый результат.

Ввод

t1 t2 ... tn

где ti — токен (число или оператор); n находится в диапазоне [0; 10000].
Вывод

Результат вычислений.

Примеры тестовых данных

Ввод

5 10 + 10 * 14 -

Вывод

136