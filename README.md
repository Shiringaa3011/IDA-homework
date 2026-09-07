# IDA-homework

Домашние задания по курсу «Интеллектуальный анализ данных» (НИУ ВШЭ). Каждое ДЗ лежит в своей папке: ноутбук с решением + датасеты, которые он использует.

## Навигация по файлам

| Папка | Ноутбук | Данные | Тема / технологии |
|---|---|---|---|
| [`hw01-numpy.ipynb`](hw01-numpy.ipynb) | — | без датасетов | Основы **NumPy**: векторизация, работа с массивами |
| [`hw02-pandas/`](hw02-pandas) | `hw02_pandas.ipynb` | `data.csv` | **Pandas**: чтение, фильтрация, агрегации на данных соцсети |
| [`hw03-eda/`](hw03-eda) | `hw03_eda.ipynb` | `train.csv`, `test.csv` | **EDA**: numpy, pandas, matplotlib, seaborn, plotly — датасет активности со смартфона (акселерометр/гироскоп) |
| [`hw04-knn-linreg/`](hw04-knn-linreg) | `hw04-knn-linreg.ipynb` | `penguins_data.csv`, `diamonds.csv` | **kNN** и линейные модели, работа с признаками (**scikit-learn**) |
| [`hw05-gd/`](hw05-gd) | `hw05_gd.ipynb` | `cars_data.csv` | **Градиентный спуск** для линейной регрессии, разные функции потерь |
| [`hw06-texts/`](hw06-texts) | `hw06_texts.ipynb` | `tweets_coronavirus.csv` | Классификация текстов (**NLP**): sentiment-анализ твитов |
| [`hw07-trees-rf/`](hw07-trees-rf) | `hw07_trees_rf.ipynb` | `diabetes.csv`, `students.csv` | **Деревья решений** и **Random Forest**, энтропия/критерий информативности вручную на numpy |
| [`hw08-boosting-clustering/`](hw08-boosting-clustering) | `hw08_boosting_clustering.ipynb` | `ds_salaries.csv` | **Градиентный бустинг** и **кластеризация** — предсказание зарплат data scientist-ов |

## Стек

Python, Jupyter Notebook, NumPy, Pandas, Matplotlib/Seaborn/Plotly, scikit-learn.

## Как открыть

```bash
git clone https://github.com/Shiringaa3011/IDA-homework.git
cd IDA-homework
jupyter notebook
```
