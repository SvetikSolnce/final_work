# Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Описание решения:
Задаем два массива. Первый массив arr1 вводим с клавиатуры через пробел. Изначально оба массива одной длины. Потом создаем метод с названием Massiv, в котором создаем цикл for. В цикле делаем проверку условия (<=3), если да то элемент первого массива заноситься в count элемент второго массива. В переменную count поочередно закидываем из первого массива во второй. После присвоение count увеличивается на 1 и возвращаеться в цикл for в котором i увеличиваеться на 1. И так до конца первого массива. Потом распечатываем полученый второй массив arr2.

**Программа находиться в папке Programma. В файле Programm.cs**

**Блок схема находиться в папке Block_shema. В файле shema.jpg**