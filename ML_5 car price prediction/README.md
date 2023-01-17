**Car price prediction**

Service for the sale of used cars "Not broken, not painted" is developing an app for attracting of new clients.
In the app you can quickly find out the market value of your car by its parameters.
We have historical data: technical specifications, complete sets and prices of cars.
Using this data we need to build ML-model to determine the car cost.

What is important for the customer:

- prediction quality;
- learning speed;
- prediction speed;

Work plan:
- analyzing of data
- predicting the data for learning;
- learning a few ML-models;
- choosing the best one and its testing

Used libraries: pandas, seaborn, sklearn (StandardScaler, OrdinalEncoder), catboost, lightgbm

As a result of the work there has been created a ML-model that determines the cost of a car by its parameters.
The model can be used in some price recommendation system or for determine suspecious ads with extremely low or high price.

___
**Определение стоимости автомобилей**

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов.
В нём можно быстро узнать рыночную стоимость своего автомобиля по его параметрам. В нашем распоряжении исторические данные: 
технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости. 

Заказчику важны:

- качество предсказания;
- скорость предсказания;
- время обучения.

План работы:
- проанализируем данные, сделаем предобработку, если понадобится;
- подготовим данные для обучения;
- обучим и сравним несколько моделей;
- выберем лучшую и протестируем ее

Использованные библиотеки: pandas, seaborn, sklearn (StandardScaler, OrdinalEncoder), catboost, lightgbm

В результате работы создана ML-модель, определяющая стоимость автомобиля по его параметрам.
Модель может быть использована в системе рекомендации цены автомобиля или для определения подозрительных объявлений с чрезвычайно низкой или высокой ценой.
