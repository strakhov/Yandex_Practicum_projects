**Prediction of taxi orders**

The company "Some Taxi Service" has collected historical data on taxi orders at airports.
To attract more drivers during peak load, we need to predict the number of taxi orders for the next hour.
We'll build a model for such a prediction.

The value of the *RMSE* metric in the test sample should be no more than 48.

Work plan:

1. Download the data and resample it one hour at a time.
2. Analyze the data.
3. Train different models with different hyperparameters. Make a test sample of 10% of the original data.
4. Check the data on the test sample and draw conclusions.


The data is in the file `taxi.csv'. The number of orders is in the `num_orders` column.
___

**Предсказание заказов такси**

Компания «Какое-то.такси» собрала исторические данные о заказах такси в аэропортах.
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.
Построим модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

План работ:

1. Загрузить данные и выполнить их ресемплирование по одному часу.
2. Проанализировать данные.
3. Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных.
4. Проверить данные на тестовой выборке и сделать выводы.


Данные лежат в файле `taxi.csv`. Количество заказов находится в столбце `num_orders`.
