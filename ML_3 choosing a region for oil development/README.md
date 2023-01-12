**Choosing a location for oil development**

Oil company "doesn't_matter_oil" needs to choose a location for drilling a well.

They gave us dataset with oil samples from 3 regions, each has with 10 000 wells.
We need to build the ML-model which will help to choose the region with maximum profit and minimum risk.
Also we have to analyze predicted profit by *Bootstrap* method.

Choosing a location steps:
- Looking for deposits in the selected region, the values of the signs are determined for each;
- Build a model and estimate the volume of stocks;
- Choose the deposits with the highest estimates of values. The number of deposits depends on the company's budget and the cost of developing one well;
- The profit is equal to the total profit of the selected fields.
___

**Выбор локации для скважины**

Нефтедобывающей компании «Бла-Бла-БлаНефть» нужно решить, где бурить новую скважину.

Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.
Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. 
А также проанализировать возможную прибыль и риски техникой *Bootstrap.*

Шаги для выбора локации:

- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.
