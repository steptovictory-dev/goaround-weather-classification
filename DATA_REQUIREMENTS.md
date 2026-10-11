# Требования к данным

Для чтения результатов достаточно публичных ноутбуков, отчетов и рисунков.

Для проверок нужны:

- research/weather-model-comparison/data/model_table_v1 – 93 файла подготовленной таблицы; SHA256 и схема в reports/02_model_table_manifest.json, реестр в configs/datasets.json.
- research/weather-model-comparison/data/primary_models_v1 – сохраненные модели Logistic и прогнозы.
- artifacts/boosting-weather-comparison – кандидаты CatBoost, параметры и выбранные модели; манифест в research/boosting-weather-comparison/reports/05_artifact_manifest.json.
- research/boosting-weather-comparison/data – сохраненные прогнозы и диагностические входы.

Локальные копии перенесены с проверкой SHA256. Публичный клон не содержит эти файлы. Подготовленная таблица происходит из европейского набора Zenodo 10210178 и погодного сопоставления Approach Risk 1.0; она не является готовым файлом исходного поставщика. Полная подготовка требует предыдущих версий и погодных файлов исходного проекта, описанных в протоколах. Историческое received_at неизвестно, задержки являются исследовательскими допущениями.

Checkpoint и статьи остаются локальными. Правила использования исходных данных определяются их источниками.
