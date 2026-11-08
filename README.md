# Проектный практикум 1 — Кейс 2: отток абонентов телеком-оператора

Ноутбук `churn_telco.ipynb`: загрузка датасета напрямую из Kaggle (Add Input в Kaggle или kagglehub) → автоотчёт ydata-profiling → EDA (countplot, KDE, boxplot/violin, Plotly scatter, Phik) → логистическая регрессия и случайный лес (ROC-кривые) → факторы риска (коэффициенты, permutation importance, SHAP) → список клиентов в зоне риска → сохранение модели.

Запуск: `pip install -r requirements.txt`, затем `jupyter notebook churn_telco.ipynb` → Run All.
Создаются файлы `eda_report.html` и `best_churn_model.joblib` (в git не попадают).
