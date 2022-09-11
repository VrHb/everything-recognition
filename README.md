# Распознование объектов на видео

Программа разпознает лица, глаза, эмоции, людей, мордашки котов в видео с помощью библиотеки opencv

## Установка

* Развернуть виртуальное окружение:
```
python -m venv env

. ./env/bin/activate
```

* Установить библиотеки `pip install -r requirements.txt`

* Запустить программу `python run.py`

## Описание функций

* is_user_wants_quit - выход из программы
* show_frame - отображает видео на экране
* draw_sqare - отображает прамоугольники в видео
* get_cascade - получает данные для распознавания из модуля config.py
