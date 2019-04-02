Сервер, клиент, инструментарий синхронизированы между собой.

Структура репозитория:

-- Server                        Сервер
   Clean.bat                     Очистка сервера от временных файлов
   Clean.sh                      Очистка сервера от временных файлов
   FOnlineServer.exe             Серверное приложение для Windows
   FOnlineServer.pdb             Символы для отладки Windows сервера, чтобы при падении дамп файл был читаемым
   FOnlineServer                 Серверное приложение для Linux
   FOnlineServerDaemon           Серверное приложение для Linux в виде демона
   FOnlineGameServer.bat         Запуск только игрового сервера
   FOnlineUpdateServer.bat       Запуск только сервера обновлений
   FOnlineServer.cfg             Конфиг файл сервера
   FOServerService.exe.lnk       Регистрация (запуск, если уже зарегестрирован) сервера как сервис (служба)
   FOServerServiceDelete.exe.lnk Удаление зарегестрированного сервиса (службы)
--- data                         Различные данные
--- dialogs                      Диалоги
    dialogs.lst                  Список диалогов и соответствующих им идентификаторов
    *.fodlg                      Файлы диалогов, открываются с помощью DialogEditor
--- dumps                        Дамп файлы
--- logs                         Логи
--- maps                         Карты
--- profiler                     Данные профайлера
--- proto                        Прототипы
--- save                         Сохраненные данные о мире и клиентах
--- scripts                      Скрипты
--- text                         Тексты
--- update                       Данные для обновления клиента

Client.zip https://yadi.sk/d/IkIO0sKQ3ZsKfb
Fullpack.zip https://yadi.sk/d/0jS-1O32lJIvvg
