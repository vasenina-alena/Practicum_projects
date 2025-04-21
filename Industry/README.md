## <font size="5"><b><u>ОПИСАНИЕ ПРОЕКТА</b></u></font>
Металлургический комбинат "Стальная птица" проводит оптимизацию производственных расходов. 
<br>Для достижения этой цели необходимо уменьшить потребление электроэнергии на этапе обработки стали. 
<br>Для этого необходимо контролировать температуру сплава.

<font size="3"><b>Задача:</b> построить модель, которая будет предсказывать температуру сплава.</font> 

## НАВЫКИ И ИНСТРУМЕНТЫ
- <b>pandas</b>
- <b>numpy</b>
- <b>matplotlib</b>
- <b>seaborn</b>
- sklearn.model_selection.<b>GridSearchCV</b>
- sklearn.ensemble.<b>RandomForestRegressor</b>
- sklearn.dummy.<b>DummyRegressor</b>
- sklearn.metrics.<b>mean_absolute_error</b>
- sklearn.pipeline.<b>Pipeline</b>
- catboost.<b>CatBoostRegressor</b>

## ОБЩИЕ ВЫВОДЫ
Обучались модели <b>RandomForestRegressor</b> и <b>CatBoostRegressor</b>.
<br>Реализованный Пайплайн позволил выявить лучшую модель: <b>CatBoostRegressor</b>. 
<br>Сравнение с результатами работы базовой модели DummyRegressor подтвердило адекватность работы реализованной модели.
