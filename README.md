# Task_result
Задача :

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. 
При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Описание решения:

Объявляем два массива: arrayNew1 и arrayNew2 такой же длины. 
Объявляем метод, в котором цикл соразмерен длине массива. 
Внутри цикла проверяется условие ( <=3 ).
Если условие удовлетворяет условие задачи - элемент массива arrayNew1 заносится в count элемент массива arrayNew2. 
Переменная count нужна, чтобы поочередно проверять данные из массива arrayNew1 и сохранять их в массив arrayNew2. 
После присвоения увеличивается переменная count на1 и возвращается к циклу for в котором i увеличивается на 1. Так проверяем все данные из массива arrayNew1 .


Графическое представление метода в папке JPG

Реализация алгоритма по пути Task_result/Program.cs
