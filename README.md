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

![123](https://user-images.githubusercontent.com/96285491/205923036-f234ac95-1fcf-4bc2-9a3b-a9409b280a27.png)


### Аргументы

Указываются при запуске программы:
1. `--start_id` - с какой книги начинать скачивание.
2. `--end_id` - до какой книги скачивать.
3. `--dest_folder` - путь к каталогу с результатами парсинга: картинкам, книгам, JSON.
4. `--skip_imgs` -  не скачивать картинки.
5. `--skip_txt` - не скачивать книги.
6. `--json_path` - указать свой путь к *.json файлу с результатами.

### Проверка результата

В папке со скриптом появится 2 новых каталога и файл .json:
![1234](https://user-images.githubusercontent.com/96285491/207607406-006848d3-2e8c-476b-8033-c5214304444f.png)

 1. `books` - В папке появятся скаченные книги

![12345](https://user-images.githubusercontent.com/96285491/205922889-6f28394b-3633-4c94-bef8-9e88459b291e.png)

 2. `images` - В папке появятся обложки книг

![123456](https://user-images.githubusercontent.com/96285491/205922937-bebd4d6d-050d-476f-ae52-b3f232aed54a.png)


### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).


