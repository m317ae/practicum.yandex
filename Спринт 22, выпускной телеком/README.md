# practicum.yandex
## Спринт 22 «Выпускной проект»
## Проект «Телеком»
## Описание проекта:    

Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
Задача: на основеретроспективных данных построить модель, которая предскажет потенциально не лояльных абонентов телекоммуникационной компании

## Используемые инструменты:

* pandas
* sklearn
* numpy
* seaborn
* phik
* catboost
* lightgbm

## Общий вывод
Через GridSearch подобраны различные гиперпараметры.Лучше всего себя проявила модель LGBMClassifier с параметрами 'max_depth': 19, 'n_estimators': 97. Ее испытали на заранее отделенной тестовой выбоке. Метрика ROC_AUC на тесте составила 0.88, что удовлетворяет условиям задачи.
