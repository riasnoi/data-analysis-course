# Занятие 3. Преобразование и объединение таблиц

На практике вы преобразуете сводку HMDA из длинной формы в широкую и обратно, добавите имена организаций через JOIN и проверите, сохранились ли исходные строки и значения. В домашней работе вы рассчитаете долю отказов по организациям.

## Лекция

- Слайды в [PDF](lecture/lecture_slides.pdf) и [PowerPoint](lecture/lecture_slides.pptx).
- Конспект в [Markdown](lecture/lecture_notes.md) и [PDF](lecture/lecture_notes.pdf).
- [Демонстрационный ноутбук](lecture/lecture_demo.ipynb) и [вопросы для повторения](lecture/lecture_questions.md).

## Практика

1. Прочитайте [условия практики](practice/guide.md).
2. Откройте [рабочий ноутбук](work/notebook.ipynb), выполните подготовку и заполните ячейки A–E.
3. Запишите письменные ответы в [отчёт практики](work/README.md).

## Домашняя работа

1. Прочитайте [условия ДЗ](practice/homework.md) и откройте [отдельный ноутбук](work/homework.ipynb). Он самостоятельно загружает исходные данные.
2. Выполните H1–H3 и заполните [отчёт ДЗ](work/homework.md). Задание H+ выполняется по желанию.

## Запуск и сдача

Запустите JupyterLab по [инструкции курса](../../README.md#подготовка-окружения). Открывайте ноутбуки в их папках lecture/ или work/ и используйте ядро «HMDA — занятие 1». Ноутбуки читают файлы из соседней папки data/. Практика и ДЗ создают папку results/. Все входные данные включены в репозиторий. Их поля и происхождение описаны в [карточке данных](data/card.md).

Перед сдачей выполните Restart Kernel → Run All. Сохраните заполненные файлы в своей копии репозитория. Практика и домашняя работа оцениваются отдельно, каждая по 10 баллов.

| Работа | Файлы для сдачи |
|---|---|
| Практика | work/notebook.ipynb, work/README.md, results/unmatched.csv, results/join_audit.json, results/organization_profile.csv |
| Домашняя работа | work/homework.ipynb, work/homework.md, results/home_denial_profile.csv, results/home_denial_groups20.csv |
