# Сбор, анализ и предобработка данных в машинном обучении

**Иноземцев Сергей Викторович · ЕТ-216**
Преподаватель: Гончаров Никита Сергеевич.

| Работа | Ноутбук | Содержание |
|---|---|---|
| [Лабораторная 2](lab2/README.md) | [lab2.ipynb](lab2/lab2.ipynb) | NumPy, статистика, Pandas и анализ заказов |
| [Лабораторная 3](lab3/README.md) | [lab3.ipynb](lab3/lab3.ipynb) | Визуализация и разведочный анализ |
| [Лабораторная 4](lab4/README.md) | [lab4.ipynb](lab4/lab4.ipynb) | Нормальность, t-тесты Уэлча и бонус Iris |


## Запуск

Создать окружение вне репозитория и установить библиотеки:

```bash
python -m venv ../susu-labs-env
../susu-labs-env/bin/python -m pip install numpy pandas scipy matplotlib seaborn openpyxl jupyterlab ipykernel
../susu-labs-env/bin/python -m jupyter lab
```

В Windows вместо `bin/python` используется `Scripts/python.exe`. Выбрать ядро созданной среды, открыть нужный ноутбук и выполнить **Restart Kernel and Run All Cells**. Чтение таблиц поддерживает запуск из корня репозитория и из папки соответствующей лабораторной.

