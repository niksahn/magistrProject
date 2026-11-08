# Проектный практикум 1 — Кейс 2: отток абонентов телеком-оператора

Ноутбук `churn_telco.ipynb`: загрузка данных по ссылке → автоотчёт ydata-profiling → EDA (доля оттока по сегментам, KDE + boxplot, Plotly scatter, Phik) → логистическая регрессия и случайный лес (матрицы ошибок + ROC-кривые) → факторы риска (коэффициенты; SHAP и permutation importance на одном графике) → список клиентов в зоне риска → сохранение модели.

Запуск: `pip install -r requirements.txt`, затем `jupyter notebook churn_telco.ipynb` → Run All.
Создаются файлы `eda_report.html` (готовый отчёт лежит в репозитории) и `best_churn_model.joblib` (в git не попадает).
