**Customers personal data protecting**

We need to protect insurance company customers personal data.\
Our target is to create the method of data transformation which makes data recovery almost impossible.\
It's important to protect the data so that the quality of machine learning models does not degrade after the transformation.\
We don't need to choose the best ML model, but it's necessarily to proove/check the algorythm works correctly.

Used libraries: numpy, pandas, seaborn, sklearn

As a result of the work there was proved that if you multiply features matrix to random invertible matrix, you securely protect the data but you still can use them for ML-algorithms with no quality loss. You can easily restore the original data by multiplying to inverted matrix.

___

**Защита персональных данных клиентов**

Нам нужно защитить данные клиентов страховой компании «ХХХ». \
Цель проекта: разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.\
Нужно защитить данные так, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. \
Подбирать наилучшую модель не требуется, но необходимо обосновать/проверить корректность работы алгоритма.

Использованные библиотеки: numpy, pandas, seaborn, sklearn

В ходе работы было доказано, что при умножении матрицы признаков на любую обратимую матрицу вы надежно защищаете данные, но все еще можете использовать их для обучения ML-моделей без потери качества. Данные легко восстанавливаются путем умножения на обратную матрицу.
