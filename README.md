# Тестовые задания
## Задание 1
Вторым способом проверки числа на четность является побитовое И (умножение) числа на двоичное число где последний бит 1. Так как в двоичном предсставление нечетные числа заканчиваются на 1, данная операция возвращает верное значение (с добавлением проверки на равность нулю).


## Задание 2
### 1
Первая реалиазация циклического буффера выполнена без использования каких либо библиотек. 
Имеет возможность обращения по отрицательнному индексу ([-1] вернет последний добавленный элемент).

### 2
Вторая реализация циклического буффера основана на очереди. Очереди задается конкретный максимальный размер при инциализации.
Использование библиотеки конпенсируется тем, что используемый код точно написан правильно и проверен многими пользователями. Также такая реализация циклического буффера указана в официальной документации python

## Задание 3
Я считаю, что самой быстрой сортировкой в данном случае (массив рандомный) будет являться quick sort. В случае частично отсортированного массива можно было бы использовать сортировку Шелла (Shell sort). Чтобы избежать потери производительности на случаях массивов, состоящих из одинаковых чисел или отсротрованных массивов я решил использовать реализацию qsort с двумя опорными элементами.
