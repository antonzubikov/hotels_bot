# **Hotel Search Bot**


Это простой телеграм бот, с помощью которого можно получать информацию об отелях, расположенных по всему миру по разным критериям. В работе используется Rapid API.

## Used technology:

* Python (3.10);
* PyTelegramBotApi (Telegram Bot framework);
* SQLite3 (database);
* requests (2.28.1);
* telebot–calendar (1.2)


## Installation:

1. Необходимо скопировать все содержимое репозитория в отдельный каталог;
2. Установить все библиотеки из requirements.txt;
3. Файл '.env.template' переименовать в '.env'. Откройте его и заполните необходимыми данными. Для этого вам надо:
    * Создать своего бота с помощью @BotFather, запросить токен;
    * Зарегистрироваться на сайте [rapidapi.com/apidojo/api/hotels4/](), скопировать API ключ (вкладка My Apps —> Ваш API ключ —> Security)
4. Запустите файл **main**.py.
