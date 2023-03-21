# TelegramRC-Bot
### Программа для дистанционного управления ПК через Telegram.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
ВНИМАНИЕ! ДАННЫЙ РЕПОЗИТОРИЙ ЯВЛЯЕТСЯ ФОРКОМ ОФИЦАЛЬНОГО (TssSaltan/TelegramRC-Bot)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Данная программа тестируется только на Windows и основные релизы будут выходить именно на Windows
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Рекомендуемые системные требования:
### ЦП:скорость 1ггц и более
### Оперативная память: 2гб и более гб
### Места на жестком диске: 1 и более гб
### Видеокарта с поддержкой DirectX
### Дисплей: 1280x720 и выше.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### ![FAQ](https://tssaltan.top/files/2019/07/Pasted.png) [FAQ + скриншоты](https://tssaltan.top/?p=1928)
### ![Download (TssSaltan version)](https://tssaltan.top/files/2019/07/download.png) [Скачать программу (Версия TssSaltan)](https://tssaltan.top/download/1931/)

## Screenshots
![Screenshot v2.0: Install 1](https://user-images.githubusercontent.com/3524731/70854539-4badd080-1ece-11ea-8570-6671c50236d8.png)
![Screenshot v2.0: Install 2](https://sun9-63.userapi.com/c858016/v858016715/1288de/pql91LytdUc.jpg)
![Screenshot v2.0: Main window](https://user-images.githubusercontent.com/3524731/70854609-fd4d0180-1ece-11ea-9d25-41c5876e9c7f.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Что нового / Changelog
### v 3.1
* Автоматическое переподключение к long-poll через указанный в настройках промежуток времени (иногда бот засыпал и не отвечал на поступаемые запросы)

### v 3.0
* Возможность работы через [собственный прокси-сервер](https://github.com/TsSaltan/Telegram-bot-api-php-proxy)
* Изменения в команде **/ram**
* Команды для windows: **/printers**, **/meta**
* Bugfix

### v 2.1
* Добавлены команды **/alert**, **/whoami**, **/keyboard**, **/browse**
* Команды для работы с таймерами: **/timer** и **/timers** [(подробнее)](https://tssaltan.top/?p=1928#timers)
* Добавлена возможность указать токен и имя пользователя в параметрах при запуске программы

### v 2.0
* Изменен внешний вид программы (в прошлой версии спойлеры ужасно лагали при редактировании)
* Поддержка прокси (пока только сервера без авторизации, DN пока не умеет корректно работать с прокси с авторизациями)
* Загрузка файлов, отправляемых пользователем в телеграм
* Кнопки клавиатуры для удобного управления
* Усовершенствован просмотр файлов (/ls)
* Отправка на печать файлов (windows only + необходим установленный microsoft word)
* Другая логика кнопок закрытия окна: закрыть - полностью закрывает программу, свернуть - сворачивает в трей.
* Возможность отключить логирование
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Build
Для сборки последней версии необходимы пакеты:
* [Telegram Bot API 1.2](https://github.com/jphp-group/jphp-telegram-bot-api/releases/)
* [Windows 2.2](https://github.com/TsSaltan/DevelNext-Windows/releases/tag/2.2)
* [Webcam 1.0.2](https://github.com/jphp-group/jphp-webcam-ext/releases/tag/1.0.3)
* SystemTray 1.0 (в составе DevelNext)
