# ИТОГОВАЯ РАБОТА

## Задача
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше,
либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.
При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Пример
**[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]**

*[“1234”, “1567”, “-2”, “computer science”] → [“-2”]*

***[“Russia”, “Denmark”, “Kazan”] → []***

## **Решение задачи**
1. Создали строчный массив
2. Определяем количество элементов в данном массиве, длина которых меньше четырёх символов. Это будет определять размер нового массива.
3. Создаем новый массив определённой ранее длины, заполняем его значениями с условием (длина элементов элементов из начлаьного массива меньше четырёх символов)
4. Выводим результаты переноса элементов

## Блок-Схема

![Блок-Схема](./Diagram/Block%20Diagram.PNG)


