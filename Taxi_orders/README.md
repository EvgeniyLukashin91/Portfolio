# Прогнозирование заказов такси

## Задача

Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. 
Построим модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

## Библиотеки

pandas, numpy, matplotlib, seaborn, statsmodels, sklearn, lightgbm, catboost

## Этапы работы

1. Загрузика данных и их ресемплирование по одному часу.
2. Анализ данных. Выполнена проверка временного ряда на стационарность, тренд и сезонность.
3. Подготовка выборок для обучения моедлей и тестирования. Обучение моедлей (LinearRegression, LightGBM, Catboost) с подбором гиперпараметров. Выбор оптимальной модели с помощью кроссвалидации и метрики RMSE
4. Проверка модели на тестовой выборке.

## Вывод
Подготовлена модель для прогнозирования количества заказов такси.
