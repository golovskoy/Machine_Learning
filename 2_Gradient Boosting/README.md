Цель: Апробация различных алгоритмов градиентного бустинга на задаче предсказания оттока клиентов банка.

Проведены предобработка и исследовательский анализ данных. Построены различные модели оттока клиентов: GradientBoostingClassifier, XGBClassifier, LGBMClassifier, CatBoostClassifier. Настройка вышеперечисленных моделей по различным параметрам: max_depth, n_estimators, max_features, learning_rate, subsample. Построение моделей с разбивкой выборки с помощью кросс-валидации (GridSearchCV). Оценка работы моделей по метрике roc_auc.

Вывод: Получил максимально возможные значения метрики roc_auc.

Использованные технологии: sklearn,xgboost, lightgbm, catboost, seaborn, matplotlib.

Статус проекта: В работе.
