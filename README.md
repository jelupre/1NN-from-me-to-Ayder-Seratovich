<h1>Метод k-ближайших соседей</h1>

Для начала выберем из уже существующего датасета "Ирисы Фишера" тренировочную выборку по ширине и длине лепестка и виду ириса. 
Создадим набор из 15 тестовых точек с ограничениями по длине и ширине лепестка. 
Отбразим тренировочную выборку. Рисуя тестовые точки, запускаем алгоритм 1NN для определения принадлежности одному из трёх существующих классов. 
В самой функции 1NN ищем ближайшего по Евклидову расстоянию соседа для текущей точки и возвращаем вид ириса для неё же. 
![screenshot of sample](https://raw.githubusercontent.com/jelupre/ML1/master/2020-09-17_23-01-43.png)