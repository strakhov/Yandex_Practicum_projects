**Mobile tariff recommendation**

Mobile provider Megaline has noticed that a lot of their clients are using old tariffs.
We need to build the recommendation system which analyzes clients behavior and offers a new tariff to a client - Smart of Ultra.

We have the dataset of users behavior which use 2 tariffs.
We should find users behavior patterns to build ML-algorithm recommending a new tariff.
Dataset contains 3214 objects with data:

*сalls* — calls number,\
*minutes* — total calls duration in minutes,\
*messages* — sms-messages number,\
*mb_used* — used internet-traffic in Mb,\
*is_ultra* — which tariff used during month («Ultra» — 1, «Smart» — 0).

Target of the task - to build ML-algorithm with *accuracy* 0.75 or more.
___


**Рекомендация тарифов**

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. 
Нам нужно построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В нашем распоряжении данные о поведении клиентов мобильного оператора, которые пользуются двумя тарифами.
Нужно найти общие паттерны поведения пользователей двух тарифов, чтобы обучить ML-модель рекомендовать пользователям тот или иной тариф. 

В нашем распоряжении датасет из 3214 строк с данными:

*сalls* — количество звонков,\
*minutes* — суммарная длительность звонков в минутах,\
*messages* — количество sms-сообщений,\
*mb_used* — израсходованный интернет-трафик в Мб,\
*is_ultra* — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

Цель задачи - построить модель с *accuracy* не меньше 0.75 на валидационной и тестовой выборках.
