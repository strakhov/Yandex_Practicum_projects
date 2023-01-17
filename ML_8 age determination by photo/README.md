**Age determination by customer photo**

Task: create and train ML-model which can determine human age by photo.
We have a dataset of 7591 pictures and their age.

Work plan:
1. Analyze data, correct learn plan
2. Create functions for data loading, creating and training model
3. Decrease MAE score on test data to 8 or less.

Used libraries: pandas, numpy, matplotlib, seaborn, keras, Adam, ResNet50

During the work on the project, a neural network based on the ResNet50 architecture was implemented, different versions of parameters and data preparation were tested. MAE of the final model = 5.97, which is significantly better than the target MAE = 8.

___
**Определение возраста покупателей**

Задача: создать и обучить модель, способную определить возраст по фото человека.
Для обучения модели в нашем распоряжении датасет из 7591 фотографий и данные по возрасту каждого из них.

План работ:
1. Проанализировать данные, возможно скорректировать план обучения
2. Создать функции загрузки данных, создания и обучения модели
3. Довести метрику МАЕ на тестовой выборке до минимальной (цель - не более 8)

Использованные библиотеки: pandas, numpy, matplotlib, seaborn, keras, Adam, ResNet50

В ходе работы надо проектом была реализована нейросеть на архитектуре ResNet50, опробованы разные версии параметров и подготовки данных. МАЕ итоговой модели = 5,97, что значительно лучше целевого значения = 8.
