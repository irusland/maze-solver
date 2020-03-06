В заданном лабиринте найти путь между двумя данными узлами.

Метод решения: Поиск в ширину.
Порядок просмотра 
узлов лабиринта 

        3
        |
    1 -- --2
        |
        4

 
Файл исходных данных :

Лабиринт.
* N - количество строк в лабиринте.
* M - количество столбцов в лабиринте.

Далее построчно расположен сам лабиринт.
Затем распологаются координаты  источника  и  цели 

в формате X Y,  где 
    X - номер строки,  
    Y - номер столбца. 

Кодировка лабиринта: 
* 1 - запрет; 
* 0 - свободно.

ПРИМЕР:
   Для лабиринта

    11111
    10101
    10001
    11111

файл данных должен быть следующим:

    4
    5
    1  1  1  1  1
    1  0  1  0  1
    1  0  0  0  1
    1  1  1  1  1
    2  2
    2  4
 
Файл результатов:

     Y
     2 2
     3 2
     3 3
     3 4
     2 4

Маршрут в лабиринте.

В случае отсутствия пути в файл результатов необходимо  записать "N",

при наличии пути "Y" и далее весь путь.
Маршрут должен начинаться координатами источника и заканчиваться координатами цели. Каждый шаг записывается с новой строки в формате X Y,  где X - номер строки, Y - номер столбца.
