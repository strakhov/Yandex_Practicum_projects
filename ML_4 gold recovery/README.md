**Recovery of gold from ore**

Preparation of a prototype of a machine learning model for the company develops solutions for the efficient operation of industrial enterprises.
The model should predict the recovery coefficient of gold from gold-bearing ore based on the ore parameters at different stages of enrichment.
We have data with ore parameters at each stage of processing at our disposal.
The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

To understand the project, it is worth getting acquainted with the technological process of gold ore enrichment.
When the extracted ore undergoes primary processing, a crushed mixture is obtained. It is sent for flotation (enrichment) and two-stage purification.

*Flotation Stage*
A mixture of gold-bearing ore is fed into the flotation plant. After enrichment, a rough concentrate and "dump tails" are obtained, that is, product residues with a low concentration of valuable metals.
The stability of this process is affected by the unstable and suboptimal physico-chemical state of the flotation pulp (a mixture of solid particles and liquid).

*Cleaning Stage*
The rough concentrate undergoes two purifications. At the output, the final concentrate and new dump tails are obtained.

*Data description*

Technological process

Rougher feed — raw materials\
Rougher additives (or reagent additives) — flotation reagents: Xanthate, Sulfate, Depressant\
Xanthate — xanthogenate (promoter, or flotation activator)\
Sulfate — sulfate (in this production sodium sulfide)\
Depressant — depressant (sodium silicate).\
Rougher process (English "rough process") — flotation\
Rougher tails — dump tails\
Float banks — flotation plant\
Cleaner process — cleaning\
Rougher Au — rough gold concentrate\
Final Au — final gold concentrate

Parameters

of the air amount stages — air volume\
fluid levels — liquid level\
feed size — the size of the raw material granules\
feed rate — feed rate

Name of signs

Template for naming features: [stage].[parameter type].[parameter name]\
Example: rougher.input.feed_ag

Possible values for the [stage] block:\
rougher — flotation\
primary_cleaner — primary cleaning\
secondary_cleaner — secondary cleaning\
final — final characteristics

Possible values for the [parameter type] block:\
input — raw material parameters\
output — product parameters\
state — parameters characterizing the current state\
of the calculation stage — design characteristics

Used libraries: pandas, seaborn, matplotlib, sklearn

As a result of the work there was created ML-model that predicts the parameters of the ore recovery product with high accuracy.
___

**Восстановление золота из руды**

Подготовка прототипа модели машинного обучения для компании разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна по параметрам руды на разных этапах обогащения предсказать коэффициент восстановления золота из золотосодержащей руды.
В нашем распоряжении данные с параметрами руды на каждом этапе обработки.
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

Для понимания проекта стоит ознакомиться с технологическим процессом обогащения золотой руды.
Когда добытая руда проходит первичную обработку, получается дроблёная смесь. Её отправляют на флотацию (обогащение) и двухэтапную очистку.

*Этап Флотация*
Во флотационную установку подаётся смесь золотосодержащей руды. После обогащения получается черновой концентрат и «отвальные хвосты», то есть остатки продукта с низкой концентрацией ценных металлов.
На стабильность этого процесса влияет непостоянное и неоптимальное физико-химическое состояние флотационной пульпы (смеси твёрдых частиц и жидкости).

*Этап Очистка*
Черновой концентрат проходит две очистки. На выходе получается финальный концентрат и новые отвальные хвосты.

*Описание данных*

Технологический процесс

Rougher feed — исходное сырье\
Rougher additions (или reagent additions) — флотационные реагенты: Xanthate, Sulphate, Depressant\
Xanthate — ксантогенат (промотер, или активатор флотации);\
Sulphate — сульфат (на данном производстве сульфид натрия);\
Depressant — депрессант (силикат натрия).\
Rougher process (англ. «грубый процесс») — флотация\
Rougher tails — отвальные хвосты\
Float banks — флотационная установка\
Cleaner process — очистка\
Rougher Au — черновой концентрат золота\
Final Au — финальный концентрат золота

Параметры этапов

air amount — объём воздуха\
fluid levels — уровень жидкости\
feed size — размер гранул сырья\
feed rate — скорость подачи

Наименование признаков

Шаблон наименования признаков: [этап].[тип_параметра].[название_параметра]\
Пример: rougher.input.feed_ag

Возможные значения для блока [этап]:\
rougher — флотация\
primary_cleaner — первичная очистка\
secondary_cleaner — вторичная очистка\
final — финальные характеристики

Возможные значения для блока [тип_параметра]:\
input — параметры сырья\
output — параметры продукта\
state — параметры, характеризующие текущее состояние этапа\
calculation — расчётные характеристики

Использованные библиотеки: pandas, seaborn, matplotlib, sklearn

В результате работы создана ML-модель, с высоким качеством предсказывающая качество продукта обогащения руды по параметрам технологического процесса.
