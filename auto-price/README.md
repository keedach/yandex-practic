# Определение стоимости автомобилей

Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. 


## Данные

В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.

## Задача

Нужно построить модель для определения стоимости.

Заказчику важны:

- качество предсказания;
- скорость предсказания;
- время обучения.

## Используемые библиотеки
`pandas` `numpy` `lightgbm` `catboost` `phik` `scikit-learn` `matplotlib`

## Результат проекта

Построены три модели CatBoost, LightGBM и RandomForestRegressor. Скорость и качество предсказаний за моделью CatBoost.
