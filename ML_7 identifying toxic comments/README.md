**Identifying toxic comment**

Online store "Wikishop" is launching a new service. Now users can edit and add product descriptions, as in wiki communities.
That is, clients offer their edits and comment on the changes of others. The store needs a tool that will search for toxic comments 
and send them for moderation.

We need to build ML-model which will classify comments to positive and negative.
For this task we have set of twitter posts with a markup about toxicity.

Our target is *F1-score* more than 0.75.

**Work plan:**

1. Upload and prepare the data.
2. Train different models.
3. Choose the best model and test it.
4. Draw conclusions.

**Data description**

The data is in the file `toxic_comments.csv'. The *text* column in it contains the comment text, and *toxic* is the target attribute.

Used libraries: pandas, numpy, re, sklearn, nltk, CatBoost, GridSearchCV

After lemmatization and vectorization of original texts, an ML model was trained that recognizes toxic comments on unfamiliar samples with high quality (F1-score=0.78).

___
**Выявление токсичных комментариев**

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах.
То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные 
комментарии и отправлять их на модерацию. 

Необходимо обучить модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор комментариев из twitter
с разметкой о токсичности.

Целевое значение метрики качества *F1* не меньше 0.75. 

**План выполнения проекта**

1. Загрузить и подготовить данные.
2. Обучить разные модели.
3. Выбрать лучшую модель и протестировать ее.
4. Сделать выводы.

**Описание данных**

Данные находятся в файле `toxic_comments.csv`. Столбец *text* в нём содержит текст комментария, а *toxic* — целевой признак.

Использованные библиотеки: pandas, numpy, re, sklearn, nltk, CatBoost, GridSearchCV

После лемматизации и векторизации текстов была обучена ML-модель, которая с высоким качеством (F1-score=0.78) распознает токсичные комментарии на незнакомых примерах.
