# Для чего этот проект? #
Здесь я просто хотел написать тесты для Джанго на Pytest и unittest. Тесты написаны для двух придложений - `news_test` (Pytest) и `note` (unittest).
# Как запустить? #
Сначала делаем виртуальное окружение и ставим зависимости:
```Bash
python -m venv .venv
source venv/bin/activate
python -m pip install -r requirements.txt
```

Чтобы запустить Pytest тесты нужно найти файл `pytest.ini` - он в папке `news_test`. Далее, просто вводим команду:
```Bash
pytest
```

Чтобы запустить unittest тесты можно передать в `note/manage.py` аргумент `test`:
```Bash
python manage,py test
```

Если очень хочется - запустить сервер для любого приложения можно через файл `manage.py`:
```Bash
python path/to/manage.py runserver
```
