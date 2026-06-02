# HW 03: EDA Human Activity Recognition

В ноутбуке
`hw03_eda_AGARKOVA_POLINA.ipynb` проводится разведочный анализ датасета [Human Activity Recognition with Smartphones](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones).

## Что внутри

- загрузка train/test данных и выбор подмножества признаков;
- проверка пропусков, дублей и баланса классов активности;
- расчет описательных статистик и корреляций;
- визуализации через `matplotlib` и `seaborn`: barplot, heatmap, pairplot,
  KDE, boxplot, violinplot, boxenplot;
- разделение активностей на статические и динамические по признакам;
- интерактивная визуализация t-SNE через `plotly`;
- заготовка для простой функции предсказания активности по EDA-правилам.
