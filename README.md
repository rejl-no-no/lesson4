# Парсер книг с сайта tululu.org

Парсер книг и сохранение их на ваше устройство.

### Как установить

Для запуска необходимы следующие компоненты:
Python 3 (установка с официального сайта)
Все зависимости указаны в файле requirements.txt

Список команд для установки вертуального окружения, установки зависимостей и запуска программы:
 1. `pip install --user pipenv` [установка окружения]
 2. `cd project_folder` [переход в папку с проектом]
 3. `pipenv shell` [переход в виртуальное окружение]
 4. `pip install -r requirements.txt` [установка необходимых пакеетов]
 5. `pipenv run python main.py` [запуск скрипта]

### Аргументы

Указываются при запуске программы:
1. `--start_page` - с какой книги начинать скачивание.
2. `--end_page` - до какой книги скачивать.

Если значения не введины, то парсер скачать с 1 по 10 книгу.

### Проверка результата

В папке со скриптом появится 2 новых каталога:
 1. `books` - В папке появятся скаченные книги
 2. `images` - В папке появятся обложки книг

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).

![image](https://user-images.githubusercontent.com/96285491/205921505-ba8d93ec-3702-4152-89b9-f0b18d0e3159.png)

