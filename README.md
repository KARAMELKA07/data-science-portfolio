# Data Science Portfolio

Привет! Меня зовут Карина Закирова. Учусь в магистратуре РТУ МИРЭА по направлению «Искусственный интеллект и машинное обучение для решения прикладных задач». Интересуюсь математикой, анализом данных и машинным обучением.

В репозитории собраны 18 учебных Jupyter Notebook по семи направлениям: подготовка данных, построение моделей, подбор гиперпараметров, оценка качества и визуализация результатов.

## Технологии

- Python, NumPy, pandas, SciPy
- scikit-learn, statsmodels, pmdarima
- Matplotlib, Seaborn, NetworkX
- Jupyter Notebook, Google Colab

## Направления и результаты

| Направление                                           | Задачи и методы                                              | Результаты экспериментов                                     |
| ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Classification](./classification/)                   | Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, GridSearchCV | 98,2% Accuracy после сокращения числа признаков с 30 до 10   |
| [Housing Regression](./housing-regression/)           | Linear Regression, Polynomial Features, Ridge, Lasso         | R²: 0,5758 → 0,6484                                          |
| [Time Series Forecasting](./time-series-forecasting/) | Тренд, сезонность, Holt, Holt-Winters, ARIMA, SARIMA         | MSE: 33 553,15 → 1 330,34 на тестовых данных Airline Passengers |
| [Neural Networks](./neural-networks/)                 | MLP, ReLU, Adam, нелинейная классификация                    | Test Accuracy: 88% → 97,5% на make_moons                     |
| [Anomaly Detection](./anomaly-detection/)             | Isolation Forest, анализ порога и гиперпараметров            | 18 из 20 синтетических выбросов, 0 ложных срабатываний на обучающих данных |
| [Clustering](./clustering/)                           | KMeans, DBSCAN, агломеративная кластеризация, Silhouette Score, ARI | Анализ геометрии кластеров, сегментация Titanic и Iris       |
| [Decision Support](./decision-support/)               | AHP, когнитивные карты, сценарное моделирование              | Ранжирование альтернатив по шести критериям, моделирование системы из семи факторов |

## Другие проекты

[Smart Wardrobe AI](https://github.com/KARAMELKA07/smart-wardrobe-ai) — дипломный full-stack проект с применением Computer Vision и рекомендательных алгоритмов.
