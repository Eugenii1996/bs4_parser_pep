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

Примененные библиотеки:
 - appdirs 1.4.4
 - attrs 21.4.0
 - beautifulsoup4 4.11.1
 - bs4 0.0.1
 - cattrs 22.1.0
 - certifi 2022.6.15
 - charset-normalizer 2.1.1
 - colorama 0.4.5
 - exceptiongroup 1.0.0rc8
 - idna 3.3
 - lxml 4.9.1
 - requests 2.28.1
 - requests-cache 0.9.5
 - six 1.16.0
 - soupsieve 2.3.2.post1
 - tqdm 4.64.0
 - url-normalize 1.4.3
 - urllib3 1.26.11
 - prettytable 2.1.0

### Клонировать репозиторий c GitHub:

```bash
git clone git@github.com:Eugenii1996/bs4_parser_pep.git
```

После клонирования необходимо установить и активировать виртуальное окружение находясь в директории bs4_parser_pep:

```bash
pyhton -m venv venv
```

Далее нужно обновить менеджер пакетов pip и установить зависимости:

```bash
pip install -r requirements.txt
```

### Запуск проекта:

Чтобы запустить проект, из директории с проектом нужно выполнить команду:

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