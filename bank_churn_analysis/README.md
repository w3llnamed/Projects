# Анализ оттока клиентов банка "Скрудж"

## Описание

Этот учебный проект был выполнен в рамках обучения профессии "Аналитик данных" на платформе Яндекс.Практикум.

Проект был выполнен в `Jupyter Notebook` на языке `Python 3` в октябре 2022 года.

## Цель проекта

Проанализировать клиентов регионального банка и выделить сегменты клиентов, которые склонны уходить из банка.

## Используемый стек

Библиотеки `Python`:
import pandas as pd
import matplotlib.pyplot as plt
import matplotlib as mpl
import seaborn as sns
import phik
from phik.report import plot_correlation_matrix
from phik import report
import numpy as np
from scipy import stats
from sklearn.linear_model import LinearRegression

## Задачи

1. Импортировать датасет и изучить общую информацию
2. Подготовить данные
3. Изучить и проверить корректность данных
4. Изучить воронку событий
5. Изучить результаты эксперимента

## Датасет

* `EventName` — название события
* `DeviceIDHash` — уникальный идентификатор пользователя
* `EventTimestamp` — время события
* `ExpId` — номер эксперимента
    * `246` и `247` — контрольные группы
    * `248` — экспериментальная
