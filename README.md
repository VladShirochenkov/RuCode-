### Основная информация
В этом ноутбуке решалась задача регрессии для предсказания цен на жилье.

### Файлы:
train.csv - обучающая выборка;
public_test.csv - тестовая выборка;
public_sample_submission_seed_0.csv - пример предсказаний.

### Метрика
MAPE.

### Формат вывода
Файл .csv с 2 колонками: id, Цена. В первой строке указаны соответствующие заголовки, в остальных строках находятся полученные данные.

### Используемые инструменты
numpy, pandas, matplotlib, seaborn, sklearn, scipy, GradientBoostingRegressor, LGBMRegressor, XGBRegressor, CatBoostRegressor, StackingCVRegressor
