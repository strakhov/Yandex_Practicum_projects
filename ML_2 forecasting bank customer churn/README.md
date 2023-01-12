**Forecasting bank customer churn**
Customers begun to leave Beta Bank. Every month. Not a lot, but noticeable. Bank marketing specialists had a research and noticed that
retaining customers is cheaper than attracting new ones.

There is a need to predict of churn bank clients. We have a dataset of users behavior and termination of contracts with the bank.

Our target is to build ML-model with maximize *F1-score*, at least 0.59. Additional metric is *AUC-ROC*.

Work plan:
1. Preparing the data for learning.
2. Learning a few models, choosing the best one.
3. Measuring F1 and AUC-ROC scores, maximizing them by sorting through different parameters.
4. Checking the best model on the test sample.

Data source: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

___
**Прогнозирование оттока клиентов из банка**

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: 
сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов 
и расторжении договоров с банком. 

Для решения задачи нужно построить модель с предельно большим значением *F1*-score, по меньшей мере 0.59 как на валидационной, так и на тестовой выборках.

Для дополнительного контроля буду использовать метрику *AUC-ROC*, и на основании двух метрик выберу модель которая наилучшим 
образом будет прогнозировать ухода клиентов.

План работы:
1. Предобработать и подготовить данные к обучению.
2. Обучить несколько моделей, выбрать наиболее подходящие.
3. Замерить метрики F1, AUC-ROC, довести их до максимума перебором параметров и\или манипуляциями с обучающей выборкой.
4. Проверить лучшую модель на тестовой выборке.

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)
