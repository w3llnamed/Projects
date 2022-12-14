# Анализ мест общественного питания и его визуализация для "Shut Up and Take My Money"

## Описание

Этот учебный проект был выполнен в рамках обучения профессии "Аналитик данных" на платформе Яндекс.Практикум.

Проект был выполнен в `Jupyter Notebook` на языке `Python 3` в октябре 2022 года.

## Цель проекта

Подготовить исследование рынка мест общественного питания Москвы, найти интересные особенности. Дать рекомендации по открытию кофейни в Москве.

### Примечание 

К сожалению, на GitHub нельзя сделать доверенным `Jupyter Notebook`, в связи с чем нет возможности просматривать интерактивные карты из пакета `folium`. Решением является просмотр проекта на платформе [nbviewer](https://nbviewer.org/github/w3llnamed/Projects/blob/main/visualization/visualization.ipynb "nbviewer.org").

## Используемый стек

Библиотеки `Python`:
* `pandas`
* `matplotlib`
* `numpy`
* `seaborn`
* `folium`
* `textwrap`


## Задачи

1. Импортировать данные и изучить общую информацию
2. Выполнить предобработку данных
3. Провести анализ данных
4. Детализировать исследование: дать рекомендации по открытию кофейни

## Датасет

* `name` — название заведения
* `address` — адрес заведения
* `category` — категория заведения
* `hours` — информация о днях и часах работы
* `lat` — широта географической точки, в которой находится заведение
* `lng` — долгота географической точки, в которой находится заведение
* `rating` — рейтинг заведения по оценкам пользователей в Яндекс Картах (высшая оценка — 5.0)
* `price` — категория цен в заведении, например «средние», «ниже среднего», «выше среднего» и так далее
* `avg_bill` — строка, которая хранит среднюю стоимость заказа в виде диапазона
* `middle_avg_bill` — число с оценкой среднего чека, которое указано только для значений из столбца `avg_bill`, начинающихся с подстроки «Средний счёт»
* `middle_coffee_cup` — число с оценкой одной чашки капучино, которое указано только для значений из столбца `avg_bill`, начинающихся с подстроки «Цена одной чашки 
* `chain` — число, выраженное 0 или 1, которое показывает, является ли заведение сетевым
* `district` — административный район, в котором находится заведение
* `seats` — количество посадочных мест
