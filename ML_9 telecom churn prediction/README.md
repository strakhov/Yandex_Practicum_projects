**Mobile provider churn prediction**

Mobile provider "Vympelphone.com" wants to predict clients churn.
If they know that client wants to change his provider he will be offered discounts and special conditions.
Our task is binary classification where the current contract has the value of the attribute 0, and the closed ones - 1.
The team gave us personal clients data, tariff information and contracts info.

We have 4 tables:
- `contract.csv` — contract information;
- `personal.csv` — clients personal data;
- `internet.csv` — online services information;
- `phone.csv` — phone services information.

Used libraries: pandas, numpy, seaborn, matplotlib, phik, sklearn (incl. OneHotEncoder, StandardScaler), CatBoost

As a result of the work there was created a ML-model predicting customer churn with high quality - ROC-AUC=0.92, Accuracy=0.87.
Correlations between features and their importance for learning were analyzed for the project. Only the most important features were selected for training the model - that accelerated the work of the algorithm. The GridSearch module helped to find the best hyperparameters of the final model.

___
**Прогнозирование оттока клиентов от мобильного оператора**

Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов.
Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.
То есть перед нами стоит задача бинарной классификации где действующий контракт имеет значение признака 0, а закрытые - 1.
Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

В нашем распоряжении 4 таблицы:
- `contract.csv` — информация о договоре;
- `personal.csv` — персональные данные клиента;
- `internet.csv` — информация об интернет-услугах;
- `phone.csv` — информация об услугах телефонии.

Использованные библиотеки: pandas, numpy, seaborn, matplotlib, phik, sklearn (incl. OneHotEncoder, StandardScaler), CatBoost

В результате работы над проектом была создана модель машинного обучения, предсказывающая уход клиента с высокой точностью: ROC-AUC=0.92, Accuracy=0.87.
Перед обучением модели были проанализированы корреляции между признаками и их важность для обучения. В итоге были отобраны только самые важные признаки, что ускорило работу алгоритма. Модуль GridSearch помог найти лучшие гиперпараметры итоговой модели.
