# ais-lab-4
The k-nearest neighbors (KNN) algorithm

`ru` **Задание**

Выбор датасета:

Четный номер в группе - Датасет [о вине](https://www.kaggle.com/datasets/davorbudimir/winedataset)

Нечетный номер в группе - Датасет [про диабет](https://www.kaggle.com/datasets/abdallamahgoub/diabetes/data)

- Проведите предварительную обработку данных, включая обработку отсутствующих значений, кодирование категориальных признаков и масштабирование.
- Получите и визуализируйте (графически) статистику по датасету (включая количество, среднее значение, стандартное отклонение, минимум, максимум и различные квантили), постройте 3d-визуализацию признаков.
- Реализуйте метод k-ближайших соседей без использования сторонних библиотек, кроме NumPy и Pandas.
- Постройте две модели k-NN с различными наборами признаков:
    - Модель 1: Признаки случайно отбираются .
    - Модель 2: Фиксированный набор признаков, который выбирается заранее.
- Для каждой модели проведите оценку на тестовом наборе данных при разных значениях k. Выберите несколько различных значений k, например, k=3, k=5, k=10, и т. д. Постройте матрицу ошибок.

`eng` **Task**

Choosing a dataset:

The even number in the group is the Dataset [about wine](https://www.kaggle.com/datasets/davorbudimir/winedataset )

The odd number in the group is the Dataset [about diabetes](https://www.kaggle.com/datasets/abdallamahgoub/diabetes/data )

- Pre-process the data, including processing missing values, encoding categorical features and scaling.
- Get and visualize (graphically) statistics on the dataset (including quantity, average, standard deviation, minimum, maximum and various quantiles), build a 3d visualization of the features.
- Implement the k-nearest neighbor method without using third-party libraries other than NumPy and Pandas.
- Build two k-NN models with different feature sets:
- Model 1: Features are randomly selected.
    - Model 2: A fixed set of features that is selected in advance.
- For each model, evaluate on a test dataset at different values of k. Select several different values of k, for example, k=3, k=5, k=10, etc. Build a matrix of errors.
