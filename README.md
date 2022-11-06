# Проект парсинга python документации

### Разработчик:

 - [Мирошниченко Евгений](https://github.com/Eugenii1996)

### О проекте:

Проект представляет собой парсер официальной документации python 
и имеет доступ к разделам:
 - Что нового
 - Последние версии python
 - Загрузка докумментации
 - Сбор данных о статусах PEP

Примененные технологии:
 - Python 3
 - bs4
 - Git
 - Pytest

### Клонирование репозитория и переход в него в командной строке:

```bash
git clone git@github.com:Eugenii1996/bs4_parser_pep.git
```

```bash
cd bs4_parser_pep
```

### Cоздать и активировать виртуальное окружение:

Виртуальное окружение должно использовать Python 3.7

```bash
pyhton -m venv venv
```

* Если у вас Linux/MacOS

    ```bash
    source venv/bin/activate
    ```

* Если у вас windows

    ```bash
    source venv/scripts/activate
    ```

### Установка зависимостей из файла requirements.txt:

```bash
python -m pip install --upgrade pip
```

```bash
pip install -r requirements.txt
```

### Запуск проекта:

Из корневой деректории проекта bs4_parser_pep выполнить команды:

```bash
python main.py {mode} {output}
```

Где "mode" является обязательным параметром, а "output" опциональным.
Список всех доступных при запуске опций можно посмотреть, воспользовавшись командой:

```bash
python main.py -h
```

или

```bash
python main.py --help
```
