# Discrete Random Variable Simulation

## English Version

### Description

This repository contains a Jupyter Notebook for simulating a discrete random variable following a negative binomial distribution. The main tasks are:
	- Generating a sample using the sum of geometric random variables algorithm.
	- Calculating and comparing empirical and theoretical mean and variance.
	- Performing a chi-squared goodness-of-fit test to verify that the sample matches the theoretical distribution.
	- Plotting theoretical and empirical cumulative distribution functions (CDFs).

### File
	- `discrete_rv_simulation.ipynb` — Jupyter Notebook with full code, explanations, and plots.

### How to run
  1. Install Python 3.11 or higher.
  2. Install matplotlib and scipy:

    pip install matplotlib scipy
  
  3.	Open the notebook in Jupyter and run all cells.

### Features
  - Step plots of empirical and theoretical CDFs.
  - Calculation of chi-squared statistic and p-value.
  - Comparison of empirical and theoretical mean and variance.
  - Tail merging to satisfy chi-squared test conditions (expected frequencies ≥ 5).

## Русская версия

### Описание
В этом репозитории реализован Jupyter Notebook для моделирования дискретной случайной величины с отрицательным биномиальным распределением. Основные задачи:

- Генерация выборки с помощью алгоритма суммы геометрических случайных величин.
- Вычисление и сравнение эмпирического и теоретического математического ожидания и дисперсии.
- Проверка соответствия распределения выборки теоретическому с помощью критерия χ².
- Построение графиков теоретической и эмпирической функции распределения (CDF).

### Файл
- `discrete_rv_simulation.ipynb` — Jupyter Notebook с полным кодом, комментариями и графиками.

### Как запустить
1. Установить Python 3.11 или выше.
2. Установить matplotlib и scipy:

```
pip install matplotlib scipy
```
3. Открыть Jupyter Notebook и выполнить все ячейки.

### Особенности
  - Ступенчатые графики эмпирической и теоретической CDF.
  - Расчёт статистики χ² и p-value.
  - Сравнение эмпирического и теоретического математического ожидания и дисперсии.
  - Объединение хвостовых категорий для выполнения условий χ²-теста (ожидаемые частоты ≥ 5).
