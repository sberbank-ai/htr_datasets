# htr_datasets
В данном репозитории находятся собранные нами и размеченные датасеты для обучения 
моделей HTR. Датасеты являются открытыми, и мы будем рады, если они окажутся полезными
для сообщества.

## Структура

В данном репозитории находится несколько папок, каждая из которых относится к своему
датасету. В каждой из папок находится свой ```README.md``` файл с подробным описанием данных,
формата, структуры, а так же ссылки для скачивания. Для некоторых задач мы так же предоставляет бейзлайн 
решения (код модели). Итак, в репозитории на данный момент содержатся следующие датасеты:

* DigitalPeter - датасет архивных рукописей Петра Первого. Содержит описание, ссылки на данные, 
а так же ноутбуки с нашим подходом к построению модели для решения данной задачи.
* IDP-forms - содержит датасет рукописных слов, написанных людьми при заполненнии специальных форм. Язык - русский.
* school_notebooks - датасет размеченных школьных тетрадей. Включает в себя информацию по двум задачам - 
локализация и перевод текста на картинке. Для задачи локализации на тетради были выделены полигонами все 
рукописные слова, для задачи распознавания - они же переведены.

В каждой из папок содержатся примеры данных.