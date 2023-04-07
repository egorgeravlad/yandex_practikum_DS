# Предсказание температуры стали

[Ноутбук](https://github.com/egorgeravlad/yandex_practikum_DS/blob/main/temp_predict/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B5%D0%BC%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D1%83%D1%80%D1%8B%20%D0%B4%D0%BB%D1%8F%20%C2%AB%D0%A2%D0%B0%D0%BA%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%BB%D1%8F%D0%B5%D0%BC%20%D1%81%D1%82%D0%B0%D0%BB%D1%8C%C2%BB.ipynb)

## Описание проекта

Металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали, чтобы оптимизировать производственные расходы. Необходимо построить модель, которая предскажет температуру стали.
Цель: построить модель предсказания температуры стали, которая будет иметь среднюю абсолютную ошибку (MAE) не больше 6.8


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **ProfileReport**
- sklearn.pipeline.**make_pipeline**
- sklearn.metrics.**make_scorer**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_absolute_error**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**
- lightgbm.**LGBMRegressor**
- **matplotlib**
- **seaborn**

## 

## Общий вывод

Построили модель предсказания температуры стали, которая имеет среднюю абсолютную ошибку (MAE) не больше 6.8 — итоговая метрика MAE на тестовой выборке достигла 6.04 градусов. Лучшей моделью оказалась LGBMRegressor. Из 5 наиболее влиятельных признаков — 2, которые мы создали дополнительно, ранее их не было в датасете
