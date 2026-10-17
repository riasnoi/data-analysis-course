# Источники для закрепления объединённой лекции

Порядок: объяснение на лекции, прогноз и демонстрация, самостоятельная работа, затем чтение соответствующего справочника. Ссылки не заменяют объяснение неизвестного инструмента. Код проверен с pandas 2.2.2 / NumPy 1.26.4.

## Слайд 5 — Зачем нужна pandas

[DataFrame](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.html), [Series](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.html).

## Слайд 6 — pd, функция, метод и атрибут

[read_csv](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.read_csv.html).

## Слайд 7 — CSV и первое чтение read_csv

[read_csv](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.read_csv.html).

## Слайд 8 — Параметры read_csv

[read_csv](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.read_csv.html).

## Слайд 9 — Неверный sep и диагностика

[read_csv](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.read_csv.html).

## Слайд 10 — dtype и сохранение идентификаторов

[read_csv](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.read_csv.html).

## Слайд 11 — nrows и usecols

[read_csv](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.read_csv.html).

## Слайд 12 — Размер, имена и типы столбцов

[shape](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.shape.html), [columns](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.columns.html), [dtypes](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.dtypes.html).

## Слайд 13 — Выбор одного столбца и Series

[Series](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.html).

## Слайд 14 — Список столбцов и двойные скобки

[DataFrame](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.html).

## Слайд 15 — head и цепочка выбора

[head](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.head.html).

## Слайд 16 — info, isna и неизвестные значения

[info](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.info.html), [isna](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.isna.html).

## Слайд 17 — value_counts и частоты категорий

[value_counts](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.value_counts.html).

## Слайд 19 — eq и isin: условия для каждой строки

[eq](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.eq.html), [isin](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.isin.html).

## Слайд 20 — sum, len и проверяемая доля

[sum](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.sum.html).

## Слайд 23 — Индекс: метка и позиция

[index](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.index.html), [set_index](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.set_index.html).

## Слайд 24 — loc и iloc

[loc](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.loc.html), [iloc](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.iloc.html).

## Слайд 25 — Фильтрация строк

[loc](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.loc.html).

## Слайд 26 — Несколько условий

[gt](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.gt.html).

## Слайд 27 — Сортировка и пять крупнейших сумм

[sort_values](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.sort_values.html).

## Слайд 28 — Вычисляемый столбец и единицы

[copy](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.copy.html).

## Слайд 29 — NumPy и векторные вычисления

[to_numpy](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.to_numpy.html).

## Слайд 30 — groupby и новая единица наблюдения

[groupby](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.groupby.html).

## Слайд 31 — agg и профиль организаций

[agg](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.core.groupby.DataFrameGroupBy.agg.html), [reset_index](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.DataFrame.reset_index.html).

## NumPy — слайд 29

[ndarray](https://numpy.org/doc/1.26/reference/arrays.ndarray.html), [broadcasting](https://numpy.org/doc/1.26/user/basics.broadcasting.html), [isnan](https://numpy.org/doc/1.26/reference/generated/numpy.isnan.html), [allclose](https://numpy.org/doc/1.26/reference/generated/numpy.allclose.html). В первой лекции требуется только умножение массива на число и понимание отсутствия pandas index.

## Задание по справочнику

Выберите уже показанный метод, найдите значение параметра по умолчанию, измените один параметр на сохранённых данных и опишите эффект на размер, тип или смысл результата. Для read_csv достаточно изучить путь, sep, dtype, nrows и usecols; весь список аргументов запоминать не нужно.

[Словарь HMDA LAR](https://ffiec.cfpb.gov/documentation/publications/loan-level-datasets/lar-data-fields/) и [локальная data card](../data/card.md) отвечают на вопрос о смысле и единицах полей.
