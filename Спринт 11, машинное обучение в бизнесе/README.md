# practicum.yandex
## Спринт 11 «Машинное обучение в бизнесе»
## Проект «Выбор локации для скважины»
## Описание проекта:    

Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. 
## Используемые инструменты:

* pandas
* numpy
* sklearn
* matplotlib
* seaborn

## Общий вывод
В рамках прроекта по разработке модели для выбора локации для разработки месторожденя рассмотрены датасеты с пробами нефти из 3_х регионов. Поставлена задача построить модель линейной регресси, которая по данным о 500 разведанных точках выберет 200 с наибольшей средней прибылью и оценит вероятность убытков. Исходя из условий задачи для разработки подходи только регион номер 1, со средней ожидаемой прибылью 424млн. руб. т.к. только в этом регионе вероятность убытков 1.2%, что подходит под заданный параметр 2.5%
