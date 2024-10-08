# Определение стоимости автомобилей

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. 
В нём можно быстро узнать рыночную стоимость своего автомобиля. 
В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. 
Вам нужно построить модель для определения стоимости. 

Заказчику важны:

- качество предсказания;
- скорость предсказания;
- время обучения.

## Цели проекта
Основной целью проекта является разработка модели машинного обучения, которая сможет предсказывать рыночную стоимость автомобиля на основе его технических характеристик, комплектации и цен на аналогичные автомобили.

## Задачи

* Изучение и подготовка предоставленных данных о технических характеристиках, комплектации и ценах автомобилей.
* Обработка пропущенных значений и аномалий в данных.
* Подготовка выборок для обучения моделей.
* Обучение различных моделей машинного обучения, включая градиентный бустинг (с использованием LightGBM) и несколько альтернативных моделей.
* Сравнение моделей по критериям заказчика: качество предсказания, время обучения и время предсказания.
* Выбор наилучшей модели и проверка её качества на тестовой выборке.

## Методы

* Изучение и подготовка предоставленных данных о технических характеристиках, комплектации и ценах автомобилей.
* Обработка пропущенных значений и аномалий в данных.
* Подготовка выборок для обучения моделей.
* Обучение различных моделей машинного обучения, включая градиентный бустинг (с использованием LightGBM) и несколько альтернативных моделей.
* Сравнение моделей по критериям заказчика: качество предсказания, время обучения и время предсказания.
* Выбор наилучшей модели и проверка её качества на тестовой выборке.

## Ожидаемые результаты

* Модель, которая соответствует требованиям заказчика по качеству предсказания, \
времени обучения и времени предсказания. 
* Модель должна иметь значение метрики RMSE меньше 2500 для того, чтобы считаться \
приемлемой для практического применения в разрабатываемом приложении.

* Данный проект позволит не только улучшить сервис\
 "Не бит, не крашен" за счёт внедрения полезной функциональности для пользователей, \
 но и продемонстрировать возможности современных методов машинного обучения в решении \
 практических задач.
 
## План

1) Подготовка данных

2) Обработка и анализ данных

3) Построение моделей
  * LightGBM
  * CatBoostReg.
  * Forest Reg.
  
4) Анализ и выводы