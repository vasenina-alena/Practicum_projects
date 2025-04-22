## <font size="5"><b><u>ОПИСАНИЕ ПРОЕКТА</b></u></font>
Интернет-магазин «Викишоп» запускает новый сервис. 
<br>Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. 
<br>То есть клиенты предлагают свои правки и комментируют изменения других. 
<br>Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

<font size="3"><b>Задача:</b> обучить модель классифицировать комментарии на позитивные и негативные.</font> 

## НАВЫКИ И ИНСТРУМЕНТЫ
- <b>pandas</b>
- <b>numpy</b>
- <b>matplotlib</b>
- nltk.stem.<b>WordNetLemmatizer</b> 
- sklearn.feature_extraction.text.<b>TfidfVectorizer</b>
- sklearn.model_selection.<b>GridSearchCV</b>
- sklearn.linear_model.<b>LogisticRegression</b>
- sklearn.ensemble.<b>RandomForestClassifier</b>
- sklearn.metrics.<b>f1_score</b>
- sklearn.pipeline.<b>Pipeline</b>
- catboost.<b>CatBoostClassifier</b>

## ОБЩИЕ ВЫВОДЫ
Была проведена леммитизация данных, очищение данных от стоп-слов, а также перевод текста в векторное представление. 
<br>По данным векторного представления были обучены модели: <b>LogisticRegression</b>, <b>RandomForestClassifier</b> и <b>CatBoostClassifier</b>. 
<br>С помощью паплайна было определено, что лучше всего с данной задачей справилась модель Логистической регрессии.
