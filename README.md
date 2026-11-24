# Домашние задания по бизнес-аналитике и ИИ

## ДЗ 1. Приоритизация обзвона клиентов банка

- [Итоговый отчёт](ДЗ%201/Итоговый%20отчёт.docx)
- [Исполняемый блокнот](ДЗ%201/Исполняемый%20файл.ipynb)
- [Исходный CSV](ДЗ%201/bank-additional-full.csv)

Блокнот и CSV находятся в одной папке. Расчёты и графики отображаются внутри блокнота, отдельные файлы результатов не создаются.

## Запуск

Для воспроизведения расчётов используется Python 3.12. Версии основных библиотек зафиксированы в `requirements.txt`, поскольку смена версии scikit-learn может изменить разбиение на выборки и результаты.

```bash
python3.12 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
cd "ДЗ 1"
jupyter lab
```

В Jupyter открыть «Исполняемый файл.ipynb» и выполнить все ячейки сверху вниз.

## Источник данных

Moro S., Rita P., Cortez P. Bank Marketing. UCI Machine Learning Repository, 2014.

- [Страница набора данных](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- [DOI: 10.24432/C5K306](https://doi.org/10.24432/C5K306)
- Лицензия набора данных: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
