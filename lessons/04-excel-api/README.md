# Занятие 4. Получение данных из Excel и API

На лекции разберём листы Excel, вложенные поля JSON, HTTP-ответ и обход нескольких страниц API. На практике вы подготовите справочник организаций из сохранённых ответов GLEIF и проверите покрытие JOIN. В ДЗ вы соберёте отдельный пакет для повторного запуска и измерите покрытие по ипотечным записям и по организациям.

## Лекция

- Слайды в [PDF](lecture/lecture_slides.pdf) и [PowerPoint](lecture/lecture_slides.pptx).
- Конспект в [Markdown](lecture/lecture_notes.md) и [PDF](lecture/lecture_notes.pdf).
- [Демонстрационный ноутбук](lecture/lecture_demo.ipynb) и [вопросы для повторения](lecture/lecture_questions.md).

## Практика

Откройте [условия](practice/guide.md) и [рабочий ноутбук](work/notebook.ipynb). Выполните A–E и заполните [отчёт](work/README.md). Для задания E заполните [шаблон предложения командного проекта](practice/proposal_template.md), обсудите его с другой группой и сохраните уточнённую версию. [Критерии практики](practice/rubric.md).

## Домашняя работа

Откройте [условия](practice/homework.md) и [отдельный ноутбук](work/homework.ipynb). Выполните H1–H3, заполните [отчёт](work/homework.md) и уточните в нём вопрос проекта с учётом обратной связи. H+ выполняется по желанию. [Критерии ДЗ](practice/homework_rubric.md).

## Запуск и сдача

Обновите зависимости из requirements.txt по [инструкции курса](../../README.md#подготовка-окружения). Открывайте ноутбуки в их папках lecture/ или work/ и выбирайте ядро «HMDA — занятие 1». Все файлы для обязательной работы находятся в data/. Поля, источники и ограничения описаны в [карточке данных](data/card.md).

Перед сдачей выполните Restart Kernel → Run All. Сохраните заполненные файлы в своей копии репозитория. Практика и домашняя работа оцениваются отдельно, каждая по 10 баллов.

| Работа | Файлы для сдачи |
|---|---|
| Практика | work/notebook.ipynb, work/README.md, results/raw/ с ответами и манифестом, results/lookup.csv, results/acquisition_report.json, results/enriched.csv, results/project_proposal.md |
| Домашняя работа | work/homework.ipynb, work/homework.md с уточнённым вопросом проекта, пакет results/homework/ целиком |
