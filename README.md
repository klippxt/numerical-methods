# Численные методы

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-notebook-F37626?logo=jupyter&logoColor=white)

Учебные работы по численным методам анализа. Реализация классических алгоритмов на NumPy с теоретическим разбором, проверкой через контрольный расчёт и оценкой точности.

## Работы

**Интерполяция и приближение**

- [hw01 — Интерполяционный полином Лагранжа](numerical-methods/hw01_lagrange_interpolation.ipynb): выбор узлов, базисные полиномы, оценка точности.
- [hw02 — Интерполяция Ньютона по узлам Чебышёва](numerical-methods/hw02_newton_chebyshev.ipynb): разделённые разности, расширение полинома новым узлом, графики ошибок.
- [hw06 — Метод наименьших квадратов](numerical-methods/hw06_least_squares.ipynb): нормальная система, полиномиальная аппроксимация, взвешенный МНК.

**Интегрирование и дифференцирование**

- [hw03 — Численное интегрирование](numerical-methods/hw03_numerical_integration.ipynb): составная формула трапеций, сравнение с аналитическим результатом.
- [hw04 — Численное дифференцирование](numerical-methods/hw04_numerical_differentiation.ipynb): первая и вторая производные, дифференцирование интерполяционного полинома.

**Собственные значения и матрицы**

- [hw10 — Степенной метод](numerical-methods/hw10_power_method.ipynb): наибольшее по модулю собственное число через отношение Рэлея.
- [hw11 — Метод вращений Якоби](numerical-methods/hw11_jacobi_eigenvalues.ipynb): полный спектр симметричной матрицы.
- [hw12 — Приближение матрицей ранга 3](numerical-methods/hw12_low_rank_approximation.ipynb): спектральное разложение, норма Фробениуса.

**Решение уравнений**

- [hw13 — Метод хорд](numerical-methods/hw13_secant_method.ipynb): локализация и итерационное уточнение корня.

## Стек

Python, NumPy, Matplotlib, Jupyter.

## Примечание

В части заданий матрицы строятся детерминированно из SHA-256 хэша индивидуального варианта, поэтому результаты полностью воспроизводимы. Каждый ноутбук содержит постановку задачи, теорию, реализацию, проверку и выводы.
